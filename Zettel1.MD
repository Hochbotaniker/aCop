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
 
 Si+1 = {0,1,2,3} <img src="https://render.githubusercontent.com/render/math?math=\cup "> {succ t1,pred t1, move t1, turn t1 | t1 <img src="https://render.githubusercontent.com/render/math?math=\in "> Si} <img src="https://render.githubusercontent.com/render/math?math=\cup "> {board t1,t2,t3,t4,tp,t0 | t1,t2,t3,t4,tp,t0 <img src="https://render.githubusercontent.com/render/math?math=\in "> Si}

b) "S0 is empty; S1 contains just the constants; S2 contains the constants plus the phrases that can be built with constants and just one succ, pred, iszero, or if; S3 contains these and all phrases that can be built using succ, pred, iszero, and if on phrases in S2; and so on. S collects together all the phrases that can be built in this way—i.e., all phrases built by some finite number of arithmetic and conditional operators, beginning with just constants." - types and programming languauges benjamin pierce

S1 = {0,1,2,3} -> S2 = {0,1,2,3, succ(t), pred(t), move(t), turn(t)} (t is a constant in T)

c) 

