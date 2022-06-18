# day-3
**JSON **

//for

 var arr = [ {"name":"raj","age":"24","color":"white"}];
  for (var i = 0; i < arr.length; i++){
  console.log(arr[i])
  }

//for in

var arr ={
 "name":"raj",
 "age":"24",
 "color":"white"
 }
 for(let key in arr)
 {
 console.log('key is' + key);
  }
  
  
  //for of
  
   var arr=[ {"name":"raj","age":"24","color":"white"},{"name":"xxx","age":"25","color":"red"},{"name":"yyy","age":"12","color":"black"} ]
 for(let ele of arr)
 {
 console.log(ele);
  }
  
  //forEach
  
   var myObj= {
 "name":"raj",
 "age":"24",
 "color":"white"
 }
    Object.keys(myObj).forEach(function(k){
    console.log(k + ' - ' + myObj[k]);
});


**Create your own resume data in JSON format**
 var myObj= {
 "Name":"Subashree.B",
 "Age":"27",
 "Mail id":"bsubashreebalakrishnan@gmail.com",
 "DOB":"28.10.1994",
  "Work exp" :"5 years",
  "Location" : "bangalore",
  "Languages known" : "tamil,english",
  "Marital status" : "Married",
   }
    Object.keys(myObj).forEach(function(k){
    console.log(k + ' : ' + myObj[k]);
});

**  **Read about the difference between window, screen and document in javascript

Window is the main JavaScript object root,  the global object in a browser, and it can also be treated as the root of the document object model. You can access it as window.

window.screen or just screen is a small information object about physical screen dimensions.

window.document or just document is the main object of the potentially visible (or better yet: rendered) document object model/DOM.
