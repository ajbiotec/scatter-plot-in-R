# scatter-plot-in-R
code for plotting all types of lines - line type (lty) can be “blank”, “solid”, “dashed”, “dotted”, “dotdash”, “longdash”, “twodash” 
x <-1:6
plot(x, type ="n", axes =FALSE, ann =FALSE)
abline(h =x, lty = x, lwd =2,mtext(x, side =2, at = x),
title("Line types"))
