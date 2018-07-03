function change_locationSelect(sel) {

  console.log(sel);
  if (sel == 'brighton') {
    
      document.getElementById('results').innerHTML = "";
      document.getElementById('results').innerHTML += '<h1> Results </h1>';
      document.getElementById('results').innerHTML += '<h4> Properties In Brighton. </h4>';
    
    $.ajax({
                  url: "https://index1.homeflow.co.uk/properties?api_key=77467477edfd2689cd77796a2c4b019f&search[address]=brighton",
                  // Handle as Text
                  dataType: "text",
                  success: function(data) {
                      // Parse JSON file
                      var json = $.parseJSON(data);
                      //Store data into a variable
                      
                      $('#searchContent').html(json.result.properties);
                      console.log(json);
                      console.log(json.result.properties);
                      //document.getElementById('searchContent').innerHTML = json.result.properties.elements[0].display_address;
                      console.log(json.result.properties.elements);
                      
                       
                      
                        document.getElementById('0').innerHTML = "";
                        document.getElementById('0').innerHTML = json.result.properties.elements[0].display_address;
                        document.getElementById('postcode0').innerHTML ="";
                        document.getElementById('postcode0').innerHTML = json.result.properties.elements[0].postcode;
                        document.getElementById('price0').innerHTML ="";
                        document.getElementById('price0').innerHTML = json.result.properties.elements[0].price;
                        document.getElementById('price0').style.borderBottom = "solid #000000"
                        
                        document.getElementById('1').innerHTML = "";
                        document.getElementById('1').innerHTML = json.result.properties.elements[1].display_address;
                        document.getElementById('postcode1').innerHTML = "";
                        document.getElementById('postcode1').innerHTML =  json.result.properties.elements[1].postcode;
                        document.getElementById('price1').innerHTML = "";
                        document.getElementById('price1').innerHTML = json.result.properties.elements[1].price;
                        document.getElementById('price1').style.borderBottom = "solid #000000"
                        
                        document.getElementById('2').innerHTML = "";
                        document.getElementById('2').innerHTML = json.result.properties.elements[2].display_address;
                        document.getElementById('postcode2').innerHTML = "";
                        document.getElementById('postcode2').innerHTML = json.result.properties.elements[2].postcode;
                        document.getElementById('price2').innerHTML = "";
                        document.getElementById('price2').innerHTML = json.result.properties.elements[2].price;
                        document.getElementById('price2').style.borderBottom = "solid #000000";
                        
                        document.getElementById('3').innerHTML = "";
                        document.getElementById('3').innerHTML = json.result.properties.elements[3].display_address;
                        document.getElementById('postcode3').innerHTML = "";
                        document.getElementById('postcode3').innerHTML = json.result.properties.elements[3].postcode;
                        document.getElementById('price3').innerHTML = "";
                        document.getElementById('price3').innerHTML = json.result.properties.elements[3].price;
                        document.getElementById('price3').style.borderBottom = "solid #000000";
                        
                        document.getElementById('4').innerHTML = "";
                        document.getElementById('4').innerHTML = json.result.properties.elements[4].display_address;
                        document.getElementById('postcode4').innerHTML = "";
                        document.getElementById('postcode4').innerHTML = json.result.properties.elements[4].postcode;
                        document.getElementById('price4').innerHTML = json.result.properties.elements[4].price;
                        document.getElementById('price4').style.borderBottom = "solid #000000";
                        
                        document.getElementById('5').innerHTML = "";
                        document.getElementById('5').innerHTML = json.result.properties.elements[5].display_address;
                        document.getElementById('postcode5').innerHTML = "";
                        document.getElementById('postcode5').innerHTML = json.result.properties.elements[5].postcode;
                        document.getElementById('price5').innerHTML = json.result.properties.elements[5].price;
                        document.getElementById('price5').style.borderBottom = "solid #000000";
                        
                        document.getElementById('6').innerHTML = "";
                        document.getElementById('6').innerHTML = json.result.properties.elements[6].display_address;
                        document.getElementById('postcode6').innerHTML = "";
                        document.getElementById('postcode6').innerHTML = json.result.properties.elements[6].postcode;
                        document.getElementById('price6').innerHTML = "";
                        document.getElementById('price6').innerHTML = json.result.properties.elements[6].price;
                        document.getElementById('price6').style.borderBottom = "solid #000000";
                        
                        document.getElementById('7').innerHTML = "";
                        document.getElementById('7').innerHTML = json.result.properties.elements[7].display_address;
                        document.getElementById('postcode7').innerHTML = "";
                        document.getElementById('postcode7').innerHTML = json.result.properties.elements[7].postcode;
                        document.getElementById('price7').innerHTML = "";
                        document.getElementById('price7').innerHTML = json.result.properties.elements[7].price;
                        document.getElementById('price7').style.borderBottom = "solid #000000";
                      
                  }
            });           
  }

  
  

  if (sel =='hove') {
    document.getElementById('results').innerHTML = "";
    document.getElementById('results').innerHTML += '<h1> Results </h1>';
    document.getElementById('results').innerHTML += '<h4> Properties In Hove. </h4>';
   $.ajax({
                  url: "https://index1.homeflow.co.uk/properties?api_key=77467477edfd2689cd77796a2c4b019f&search[address]=hove",
                  // Handle as Text
                  dataType: "text",
                  success: function(data) {
                      // Parse JSON file
                      var json = $.parseJSON(data);
                      //Store data into a variable
                      
                      $('#searchContent').html(json.result.properties);
                      console.log(json);
                      console.log(json.result.properties);
                      //document.getElementById('searchContent').innerHTML = json.result.properties.elements[0].display_address;
                      console.log(json.result.properties.elements);
                      
                        document.getElementById('0').innerHTML = "";
                        document.getElementById('0').innerHTML = json.result.properties.elements[0].display_address;
                        document.getElementById('postcode0').innerHTML ="";
                        document.getElementById('postcode0').innerHTML = json.result.properties.elements[0].postcode;
                        document.getElementById('price0').innerHTML ="";
                        document.getElementById('price0').innerHTML = json.result.properties.elements[0].price;
                        document.getElementById('price0').style.borderBottom = "solid #000000"
                        
                        document.getElementById('1').innerHTML = "";
                        document.getElementById('1').innerHTML = json.result.properties.elements[1].display_address;
                        document.getElementById('postcode1').innerHTML = "";
                        document.getElementById('postcode1').innerHTML =  json.result.properties.elements[1].postcode;
                        document.getElementById('price1').innerHTML = "";
                        document.getElementById('price1').innerHTML = json.result.properties.elements[1].price;
                        document.getElementById('price1').style.borderBottom = "solid #000000"
                        
                        document.getElementById('2').innerHTML = "";
                        document.getElementById('2').innerHTML = json.result.properties.elements[2].display_address;
                        document.getElementById('postcode2').innerHTML = "";
                        document.getElementById('postcode2').innerHTML = json.result.properties.elements[2].postcode;
                        document.getElementById('price2').innerHTML = "";
                        document.getElementById('price2').innerHTML = json.result.properties.elements[2].price;
                        document.getElementById('price2').style.borderBottom = "solid #000000";
                        
                        document.getElementById('3').innerHTML = "";
                        document.getElementById('3').innerHTML = json.result.properties.elements[3].display_address;
                        document.getElementById('postcode3').innerHTML = "";
                        document.getElementById('postcode3').innerHTML = json.result.properties.elements[3].postcode;
                        document.getElementById('price3').innerHTML = "";
                        document.getElementById('price3').innerHTML = json.result.properties.elements[3].price;
                        document.getElementById('price3').style.borderBottom = "solid #000000";
                        
                        document.getElementById('4').innerHTML = "";
                        document.getElementById('4').innerHTML = json.result.properties.elements[4].display_address;
                        document.getElementById('postcode4').innerHTML = "";
                        document.getElementById('postcode4').innerHTML = json.result.properties.elements[4].postcode;
                        document.getElementById('price4').innerHTML = json.result.properties.elements[4].price;
                        document.getElementById('price4').style.borderBottom = "solid #000000";
                        
                        document.getElementById('5').innerHTML = "";
                        document.getElementById('5').innerHTML = json.result.properties.elements[5].display_address;
                        document.getElementById('postcode5').innerHTML = "";
                        document.getElementById('postcode5').innerHTML = json.result.properties.elements[5].postcode;
                        document.getElementById('price5').innerHTML = json.result.properties.elements[5].price;
                        document.getElementById('price5').style.borderBottom = "solid #000000";
                        
                        document.getElementById('6').innerHTML = "";
                        document.getElementById('6').innerHTML = json.result.properties.elements[6].display_address;
                        document.getElementById('postcode6').innerHTML = "";
                        document.getElementById('postcode6').innerHTML = json.result.properties.elements[6].postcode;
                        document.getElementById('price6').innerHTML = "";
                        document.getElementById('price6').innerHTML = json.result.properties.elements[6].price;
                        document.getElementById('price6').style.borderBottom = "solid #000000";
                        
                        document.getElementById('7').innerHTML = "";
                        document.getElementById('7').innerHTML = json.result.properties.elements[7].display_address;
                        document.getElementById('postcode7').innerHTML = "";
                        document.getElementById('postcode7').innerHTML = json.result.properties.elements[7].postcode;
                        document.getElementById('price7').innerHTML = "";
                        document.getElementById('price7').innerHTML = json.result.properties.elements[7].price;
                        document.getElementById('price7').style.borderBottom = "solid #000000";
                      
                  }
            }); 
      
   
   
  }
  
  if(sel =='worthing'){
     document.getElementById('results').innerHTML = "";
     document.getElementById('results').innerHTML += '<h1> Results </h1>';
   document.getElementById('results').innerHTML += '<h4> Properties In Worthing. </h4>';
   
   $.ajax({
                  url: "https://index1.homeflow.co.uk/properties?api_key=77467477edfd2689cd77796a2c4b019f&search[address]=worthing",
                  // Handle as Text
                  dataType: "text",
                  success: function(data) {
                      // Parse JSON file
                      var json = $.parseJSON(data);
                      //Store data into a variable
                      
                      $('#searchContent').html(json.result.properties);
                      console.log(json);
                      console.log(json.result.properties);
                      //document.getElementById('searchContent').innerHTML = json.result.properties.elements[0].display_address;
                      console.log(json.result.properties.elements);
                      
                        document.getElementById('0').innerHTML = "";
                        document.getElementById('0').innerHTML = json.result.properties.elements[0].display_address;
                        document.getElementById('postcode0').innerHTML ="";
                        document.getElementById('postcode0').innerHTML = json.result.properties.elements[0].postcode;
                        document.getElementById('price0').innerHTML ="";
                        document.getElementById('price0').innerHTML = json.result.properties.elements[0].price;
                        document.getElementById('price0').style.borderBottom = "solid #000000"
                        
                        document.getElementById('1').innerHTML = "";
                        document.getElementById('1').innerHTML = json.result.properties.elements[1].display_address;
                        document.getElementById('postcode1').innerHTML = "";
                        document.getElementById('postcode1').innerHTML =  json.result.properties.elements[1].postcode;
                        document.getElementById('price1').innerHTML = "";
                        document.getElementById('price1').innerHTML = json.result.properties.elements[1].price;
                        document.getElementById('price1').style.borderBottom = "solid #000000"
                        
                        document.getElementById('2').innerHTML = "";
                        document.getElementById('2').innerHTML = json.result.properties.elements[2].display_address;
                        document.getElementById('postcode2').innerHTML = "";
                        document.getElementById('postcode2').innerHTML = json.result.properties.elements[2].postcode;
                        document.getElementById('price2').innerHTML = "";
                        document.getElementById('price2').innerHTML = json.result.properties.elements[2].price;
                        document.getElementById('price2').style.borderBottom = "solid #000000";
                        
                        document.getElementById('3').innerHTML = "";
                        document.getElementById('3').innerHTML = json.result.properties.elements[3].display_address;
                        document.getElementById('postcode3').innerHTML = "";
                        document.getElementById('postcode3').innerHTML = json.result.properties.elements[3].postcode;
                        document.getElementById('price3').innerHTML = "";
                        document.getElementById('price3').innerHTML = json.result.properties.elements[3].price;
                        document.getElementById('price3').style.borderBottom = "solid #000000";
                        
                        document.getElementById('4').innerHTML = "";
                        document.getElementById('4').innerHTML = json.result.properties.elements[4].display_address;
                        document.getElementById('postcode4').innerHTML = "";
                        document.getElementById('postcode4').innerHTML = json.result.properties.elements[4].postcode;
                        document.getElementById('price4').innerHTML = json.result.properties.elements[4].price;
                        document.getElementById('price4').style.borderBottom = "solid #000000";
                        
                        document.getElementById('5').innerHTML = "";
                        document.getElementById('5').innerHTML = json.result.properties.elements[5].display_address;
                        document.getElementById('postcode5').innerHTML = "";
                        document.getElementById('postcode5').innerHTML = json.result.properties.elements[5].postcode;
                        document.getElementById('price5').innerHTML = json.result.properties.elements[5].price;
                        document.getElementById('price5').style.borderBottom = "solid #000000";
                        
                        document.getElementById('6').innerHTML = "";
                        document.getElementById('6').innerHTML = json.result.properties.elements[6].display_address;
                        document.getElementById('postcode6').innerHTML = "";
                        document.getElementById('postcode6').innerHTML = json.result.properties.elements[6].postcode;
                        document.getElementById('price6').innerHTML = "";
                        document.getElementById('price6').innerHTML = json.result.properties.elements[6].price;
                        document.getElementById('price6').style.borderBottom = "solid #000000";
                        
                        document.getElementById('7').innerHTML = "";
                        document.getElementById('7').innerHTML = json.result.properties.elements[7].display_address;
                        document.getElementById('postcode7').innerHTML = "";
                        document.getElementById('postcode7').innerHTML = json.result.properties.elements[7].postcode;
                        document.getElementById('price7').innerHTML = "";
                        document.getElementById('price7').innerHTML = json.result.properties.elements[7].price;
                        document.getElementById('price7').style.borderBottom = "solid #000000";
                      
                  }
            });           
  }
  
}


