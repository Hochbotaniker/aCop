 ## Aufgabe U.1.1
 ### a)
 Induktiv: {0,1,2,3} <img src="https://render.githubusercontent.com/render/math?math=\subseteq "> T
 
if t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T then {succ t1, pred t1, move t1, turn t1} <img src="https://render.githubusercontent.com/render/math?math=\in ">  T
 
if t1,t2,t3,t4,tp,t0 <img src="https://render.githubusercontent.com/render/math?math=\in "> T then {board t1,t2,t3,t4,tp,t0} <img src="https://render.githubusercontent.com/render/math?math=\in ">  T
 
 Als System von Inferenzregeln: 0 <img src="https://render.githubusercontent.com/render/math?math=\in "> T, 1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T, 2 <img src="https://render.githubusercontent.com/render/math?math=\in "> T, 3 <img src="https://render.githubusercontent.com/render/math?math=\in "> T
 
 t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T / succ t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T
 
 t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T / pred t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T
 
 t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T / move t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T
 
 t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T / turn t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T
 
 t1,t2,t3,t4,tp,t0 <img src="https://render.githubusercontent.com/render/math?math=\in "> T / board t1,t2,t3,t4,tp,t0 <img src="https://render.githubusercontent.com/render/math?math=\in ">  T
	
	
 Konkret, als die kumulativen Mengen S0 und Si+1:
 
 S0 =  <img src="https://render.githubusercontent.com/render/math?math=\emptyset ">
 
 Si+1 = {succ t1,pred t1, board t1, move t1, turn t1 | t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> T}
