# CODE SNIPPET IDEA
 
 Anlegen neue Vorlesung:
 
 ## Deklaration von Instanzen eines Objektes 
 TimeWindow sose := new TimeWindow(Start.Date=20-04-2020,End.Date=17-04-2020);
 Event exp := new Event(Title="Vorlesung Forgeschrittene Konzepte der Programmierung", 
                        TimeWindow=sose,Weekday=WEDNESDAY,BeginTime=10:15, EndTime=11:45,
                        weekly=true);

## Bedingungen
if (sose.Start.Date = "20-04-2020") {
    System.out.println("Stimmt");
} elseIf (sose.Start.Date < "20-04-2020") {
    System.out.println("Sie sind in einem einem FS vor SoSe2020");
} elseIf (sose.Start.Date > "20-04-2020") {
} else {
    System.out.println("Sie sind in einem einem FS nach SoSe2020");
}

## Schleife
TimeWindow sose2[] := new TimeWindow()[5];
for (int i = 0; i < 5; i++)
{
// Hochzählen der Sommersemester
   sose2[i].Start.Date = sose.Start.Date + i;
   sose2[i].End.Date   =  sose.End.Date + i;
}
