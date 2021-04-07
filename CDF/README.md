# Cummulative Distributive Function
This is the file for the implementation of the Cummumlative Distributive Function.
CDF is the distributive function of X such that X takes values less than or equal to x.

<p align="center">
<img src="http://www.sciweavers.org/tex2img.php?eq=%20F_%7BX%7D%28x%29%20%3D%20P%28X%3C%3Dx%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="5 solid #fff;" alt=" F_{X}(x) = P(X<=x)" width="160" height="18" />
</p>
<br>
The CDf defines the proportion of the data below a cutoff a. To define the proportion of values above a, we will compute:

<p align="center">
<img src="http://www.sciweavers.org/tex2img.php?eq=1%20-%20F%28a%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="1 - F(a)" width="69" height="18" />
</p>

To define the proportion of values  between a and b, we compute:

<p align="center">
<img src="http://www.sciweavers.org/tex2img.php?eq=F%28b%29%20-%20F%28a%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="F(b) - F(a)" width="94" height="18" />
</p>

Following plot is the output of the CDF function.

<img src="cdf_output.jpg">
