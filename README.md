WSDL ::  http://localhost:8080/spring-webservices-sample/endpoints/AccountDetailsService.wsdl
Available Currency Types : "LKR","INR","JPY","GBP","AUD","EUR","USD","OMR"

Request xml: 
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:acc="http://com/blog/samples/webservices/accountservice">
   <soapenv:Header/>
   <soapenv:Body>
      <acc:CurrencyRequest>
         <acc:Currency>?</acc:Currency>
         <acc:Value>?</acc:Value>
      </acc:CurrencyRequest>
   </soapenv:Body>
</soapenv:Envelope>

** for user: Value = 0;
** if change the value of the currency, use "Value" by admin
