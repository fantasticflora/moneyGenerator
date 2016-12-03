<html>
<div id="Page1" class="page" style="">
  <div style="background-color:white; padding:10px;">
    <h1 style="font-family:verdana; text-align:center; font-size:280%;">Money Maker</h1>
    <h2 style="font-family:courier; text-align:center;">How to be rich in minutes!</h2>
    <h4 style="text-align:center;" >Ever wondered how to get rich quick?</h4>
    <h4 style="text-align:center;" >This is the Answer! </h4>
      <div style="background-color:silver;color:black;padding:25px;">
        <p>People have often struggled with money, and with our current     declining economy, the problem isn't going to get any better. Lately, with the increase in taxes for the federal government and a higher cost of living, many people are struggling to make enough to live. </p>
      </div>
    <h4 style="text-align:center;">Why wait and struggle along with everyone else if you can elevate</h4>
    <h3 style="text-align:center;">YOURSELF</h3>
    <h4 style="text-align:center;">higher standing?</h4>
    <h2 style="text-align:center; background-color:silver;color:black;padding:25px;">This is the solution you've been waiting for! </h2>
  <p style="text-align: center;">I want to become  <span onclick="show('Page2');">wealthy!</span>
</p>
  </div>
</div>
<div id="Page2" class="page" style="display:none">
   <div style="font-family:verdana; background-color:white; padding:15px;">
   <div style="text-align: center;">
     <h1>
     Money Maker
     </h1>
     <h3>
     How to Begin your new Life!
     </h3>
     </div>
     </div>
     <p>
       At MoneyMaker©, we value our fellow people. We understand that you may have some doubts on our ability to help you. 
       If you are not satisfied with us, we will gladly assist you in choosing a better financial plan, or retract the money given to you. 
     </p>
     <p>
      To prevent unlawful use of information, all information entered will not be disseminated. Additionally, we will not release information to any third-party systems. 
     </p>
     <p>
     Hello, I am Flora, also known as Bot A-7713. I was assigned to you at 
     </p>
     <p id="date"></p>
     <p>
     I am here to help you with your new financial profile. 
     </p>
     <p>
     Please click on "I agree with the terms" if you agree with the above terms and would like to continue.
     </p>
     <p style="text-align: center; background-color:silver;color:black;padding:25px;"><span onclick="show('Page3');">I agree with the terms</span>
</p>
     <script>
document.getElementById("date").innerHTML = Date();
</script>
   </div>
<div id="Page3" class="page" style="display:none">
    <div style="background-color:white; padding:10px;">
    <h1 style="font-family:verdana; text-align:center; ">Money Maker</h1>
    <p>
    Thanks for choosing Money Maker! We are here to be your one-way ticket to a luxurious life, and the easy road to relaxation. You will be able to attend opulent, five-star parties, and get immersed with life around the big names. Who knew there was an easy route for life?
    </p>
    <p>
     Once again, Thank you for choosing Money Maker! As your assistant, I am here to help you through the process of raising money. To receive the money, please fill out the form on the next page. None of the information will be disseminated, as stated by our terms of agreement. 
     </p>  
     <p>
     Bot Flora
     </p>
 
<span style="text-align:center" onclick="show('Page4');">Form</span>

 </div>
</div>
<div id="Page4" class="page" style="display:none">
    <p>
    Please proceed to fill out this information:
    </p>
    
    <span onclick="show('Page5');">DEFAULT MOVING ON BUTTON</span>
</div>


<div id="Page5" class="page" style="display:none">
 <div style="background-color:white; padding:10px;">
 <h1 style="font-family:verdana; text-align:center; font-size:280%;">Money Maker</h1>
   <p>
   Thank you for filling out the form. 
   The default amount of money selected is: (250,000.00) in (US Dollars).
   Please refrain from changing this amount until processing and checkout. 
   </p>
   <p>
   Due to inflation and other economic effects, we are not able to supply you with any immediate order of over (999,999.99) in US Dollars. Those orders will not be processed, and will not be delivered. 
   </p>
   <p>
   Instead, you may place multiple orders, each at least one week (7 days) apart, and build your fortune from there. 
   </p>
   <p>
     Bot Flora
   </p>

<div id="Page6" class="page" style="display:none">
    Content of page 6
</div>
</div>
</div>
</html>

<script>
function show(elementID) {
    var ele = document.getElementById(elementID);
    if (!ele) {
        alert("no such element");
        return;
    }
    var pages = document.getElementsByClassName('page');
    for(var i = 0; i < pages.length; i++) {
        pages[i].style.display = 'none';
    }
    ele.style.display = 'block';
}
</script>



