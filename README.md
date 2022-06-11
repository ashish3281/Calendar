# Calendar
<p>C program to display month by month calendar for a given year.
Given a year N , the task is to print the calendar for every month of the given year.
</p>
<br>
<p>using this formula to find the the last weekday </p>
<pre>
int get_1st_weekday(int year){
    int d;
  d = (((year-1)*365)+((year-1)/4)-((year-1)/100)+((year)/400)+1)%7;
 return d;
}
</pre>
<br>
<p>using this formula to find the year is a leap year or not</p>
<pre>
 if((year%4==0 && year%100!=0)||(year%400==0))
 </pre>
<br>
<h2>output</h2>

![Screenshot (256)](https://user-images.githubusercontent.com/92047366/173171549-da5e5fd3-54e6-448b-bd31-1a9958408c9d.png)
![Screenshot (257)](https://user-images.githubusercontent.com/92047366/173171538-5b0ec982-da02-4faa-b6d6-d5259d4893c7.png)
![Screenshot (258)](https://user-images.githubusercontent.com/92047366/173171578-00a98925-9437-425e-87f6-957f30666a88.png)
![Screenshot (259)](https://user-images.githubusercontent.com/92047366/173171585-23e88717-a657-4dc5-b5a5-26f12de61352.png)
![Screenshot (260)](https://user-images.githubusercontent.com/92047366/173171605-4f4bab56-7b67-439a-bfb9-845a852e61d0.png)
