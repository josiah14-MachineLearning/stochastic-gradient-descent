# Stochastic Gradient Descent

This repository holds implementations of various forms of Stochastic Gradient Descent in various programming languages.

The basic equation is as follows: 

![equation](http://www.sciweavers.org/tex2img.php?eq=Basic%20Stochastic%20Gradient%20Descent%0A%0A%24e_%7Bui%7D%24%20is%20the%20associated%20prediction%20error%20%0A%0A%20%24q_i%5ET%5Ccdot%20p_u%24%20yields%20a%20rating%20prediction%20from%20user%20%24u%24%20to%20item%20%24i%24%0A%0A%20%24r_%7Bui%7D%24%20is%20a%20known%20user%20to%20item%20ranking%20from%20user%20%24u%24%20to%20item%20%24i%24%0A%0A%20%24p_u%24%20is%20user%20%24u%24%27s%20latent%20factors%20vector%0A%0A%20%24q_i%24%20is%20item%20%24i%24%27s%20latent%20factors%20vector%0A%0A%20%24%5Cgamma%24%20is%20the%20learning%20rate%20constant%0A%0A%20%24%5Clambda%24%20is%20also%20a%20constant%20value%0A%0A%24%24%0Ae_%7Bui%7D%20%3A%3D%20r_%7Bui%7D%20-%20q%5ET_i%5Ccdot%20p_u%0A%24%24%0A%24%24%0Aq_i%20%5Cleftarrow%20q_i%20%2B%20%5Cgamma%5Ccdot%28e_%7Bui%7D%5Ccdot%20p_u%20-%20%5Clambda%5Ccdot%20q_i%29%0A%24%24%0A%24%24%0Ap_u%20%5Cleftarrow%20p_u%20%2B%20%5Cgamma%5Ccdot%28e_%7Bui%7D%5Ccdot%20q_i%20-%20%5Clambda%5Ccdot%20p_u%29%0A%24%24%0A%0A%0AThe%20above%20calculations%20are%20run%20iteratively%20until%20convergence%20upon%20a%20minimized%20%24e_%7Bui%7D%24%20value.&bc=White&fc=Black&im=png&fs=12&ff=arev&edit=0a)
