# rotating-circle

Animate a dotted circular in rotate route by CSS
<br/>
duration rotate and dots are editable.
duration rotate time is based on <b>--duration-time</b> defined in :root CSS.
<br/>
and destination of between dots is based on :
<pre>
transform: rotateZ(calc(var(--index-of-dot) * calc(180deg/--number-of-dots)));
</pre>
screen-01
![Screenshot 2022-01-24 at 12-20-24 Practice CSS](https://user-images.githubusercontent.com/13866803/150753585-a3dad548-b455-48e2-a655-d79f0e8db4fd.png)
screen-02
![Screenshot 2022-01-24 at 12-20-42 Practice CSS](https://user-images.githubusercontent.com/13866803/150753550-6758e7ed-e34b-4177-8cf7-1bcea7e155ed.png)
screen-03
![Screenshot 2022-01-24 at 12-20-52 Practice CSS](https://user-images.githubusercontent.com/13866803/150753600-3ba2d26a-befa-48cd-81ce-1421e06367a7.png)


and this will continue.

