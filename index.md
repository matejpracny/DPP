---
title       : Body Mass Index Calculator
subtitle    : Developing Data Products Project
author      : Matej Pracny
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- 
## BMI - Introduction
  
The body mass index is a measure of relative size based on the mass and height of an individual. The index was devised by Adolphe Quetelet between 1830 and 1850. The BMI for a person is defined as their body mass divided by the square of their height. So if the weight is in kilograms and the height in metres, the result is immediate. If pounds and inches are used the result must be converted. Therefore metric system is used for the model.

BMI Range:

- BMI <18.5: Underweight
- BMI 18.5-24.9: Normal weight
- BMI 25-29.9: Overweight
- BMI >30: Obesity

---  
## BMI Table

Detailed BMI table for different heights and weights is shown bellow:

<!-- Limit image width and height -->
<style type='text/css'>
img {
    max-height: 560px;
    max-width: 964px;
}
</style>

<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

!['BMI Table'](http://www.shape.com.my/wp-content/uploads/BMI_table.jpg)


---  
## BMI Calculator - Ilustration

<!-- Limit image width and height -->
<style type='text/css'>
img {
    max-height: 560px;
    max-width: 964px;
}
</style>

<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

!['BMI'](figures/BMI.png)


BMI calculator is published at: http://matejpracny.shinyapps.io/BMI_Index.

---  
## Results interpretation

BMI Calculator is easyly used. It is necesary to input only weight (in kg) and height (in cm) to the aplication to calculate BMI index. It is necesary to click the submit button to calculte BMI after imputing the variables into the model or to recalculate the BMI after changing the variables. After submitting the variables BMI is calculated and corresponding result is displayed. If the BMI is under 18.5 the person is underweight, if between 18.5-24.9 he/she has normal weight. There is a risk of overweight If a person has BMI between 25-29.9 risk of obesity if the BMI is higher than 30.

BMI should be used only as a rought guide. Person's weight and therefore BMI index could highly depend on the personal body strenght and body muscle. Therefore more muscular people could be classified by the BMI as overwieght even when they are not. Also because the BMI depends upon weight and the square of height, it ignores basic scaling laws whereby mass increases to the 3rd power of linear dimensions. Hence, larger individuals, even if they had exactly the same body shape and relative composition, always have a larger BMI.
