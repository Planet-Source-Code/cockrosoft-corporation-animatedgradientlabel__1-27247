<div align="center">

## AnimatedGradientLabel


</div>

### Description

Making Animated Gradien Label.

Changing the background of a label.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[cockrosoft corporation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/cockrosoft-corporation.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/cockrosoft-corporation-animatedgradientlabel__1-27247/archive/master.zip)





### Source Code

'Add 1 labelbox and timer to your form<br>
'<br>
'Name the labelbox as Label1<br>
'<br>
'Name the timer as Timer1<br>
'
'Insert the following code to your form:<br>
 Private Sub Timer1_Timer()<br>
 Static A<br>
  A = A + 10: If A > 510 then A = 0<br>
'To change the effect, put other numbers<br>
'insted of the 0 below.<br>
'<br>
'You can also replace places betwwen <br>
'the 'Abs '(A-256))' and one of the zeros<br>
'below.<br>
'To decrease the pace of the animation, <br>
'increase the timer interval property.<br>
<br>
Label1.BackColor = RGB(Abs(A - 256),0,0)<br>
<br>
End Sub

