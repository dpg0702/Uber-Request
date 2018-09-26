# Uber-Request
var UberApi = require('uber-api-gb');
var uberApi = new UberApi('YOUR_SERVER_KEY');
uberApi.getProductById({'product_id':'24230831-a2a3-4f8f-a952-405d11caf343'},function(error,response){
      'use strict';
      if(error){
        console.log(error);
      }else{
       console.log(response);
      }
});


Request an Uber
