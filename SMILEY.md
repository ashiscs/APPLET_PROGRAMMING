```
import java.applet.*;
import java.awt.*;
public class helloworld extends Applet
{
	
    public void paint(Graphics g)
    {
        g.drawOval(80, 70, 150, 150);
        
        g.setColor(Color.GREEN);
        
        g.fillOval(120,120,15,15);
        g.fillOval(170, 120, 15, 15);
        //g.drawLine(100,30,20,10);
        
        g.drawArc(130, 180, 50, 20, 180, 180);
   }
}
```
