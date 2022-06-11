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
