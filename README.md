<p align="center"><a href="https://dreywandowski.xyz/helpful_links/1064.svg" target="_blank"><img src="https://dreywandowski.xyz/images/10624.svg" width="350" height="150"></a></p>

<p align="center">
<a href="#"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="#"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="#"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="#"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## <u>HELPFUL LINKS</u>

These are some random links that have helped me out over the years regarding some issues I face at work.
I will try as much as possible to group them by categories for easy search and reference purposes.

<details>
  <summary><h4>HTML/CSS</h4></summary>
    ## Heading
  1. <i><a href="https://sweetalert2.github.io/"> Make awesome alerts for Web projects</a></i>
      
</details>
<details>
  <summary><h4>Javascript</h4></summary>
1. Regex for nigerian phone number:
```
   var regex2    = /234\d{11}$/; //For Phone Numbers in International Format (234xxxxxxxxxx)
     var gsm       = '23436377723000';
     var verify = gsm.includes("+");
     if(!gsm.match(regex2) || (verify)){
       console.log("Invalid Phone Number Specified. \nEnter Right Digit either in International Format 234xxxxxxxxxx");
      
     }
   
     else{
       console.log('coollllll, working' + verify );
       } ``` 
</details>
<details>
  <summary><h4>PHP</h4></summary>
  
  1. <i><a href="https://twitter.com/dreywandowski/status/1346514361725186049/"> Autoload</a></i>
      
</details>
<details>
  <summary><h4>Laravel</h4></summary>
  
  1. <i><a href="https://sweetalert2.github.io/"> Make awesome alerts for Web projects</a></i>
      
</details>
<details>
  <summary><h4>Linux/Apache/Webhosting</h4></summary>
  
  1. <i><a href="https://sweetalert2.github.io/"> Make awesome alerts for Web projects</a></i>
      
</details>
<details>
  <summary><h4>MySQL</h4></summary>
  
  1. Left Outer Join == Left Outer Join:
                          SELECT hmrs_persdet.staffid, title,surname,othnames,gender,mstatus,DATE_FORMAT(dofbirth,'%d/%m/%Y') as dofbirth,branch, nrank,nrank,DATE_FORMAT(dofemp,'%d/%m/%Y') as dofemp,DATE_FORMAT(confdate,'%d/%m/%Y') as confdate,emptype, dept,sstatus,superv,dept,sstate, CONCAT(saddr1,' ', saddr2,' ', saddr3) as address , semail as emails, conemail  as cemails, sgsm  as gsm, fname, desig  FROM `hmrs_persdet`
                        
                                        LEFT JOIN hmrs_contact as contact
                        
                                        on hmrs_persdet.staffid = contact.staffid
                        
                                        LEFT JOIN hmrs_uploads as uploads
                                        on hmrs_persdet.staffid = uploads.staffid
                        
                                        WHERE (docclass ='PHO')
                        
                                        and $this->status";
  2. Subquery:
   ```
   ``"SELECT staffid,title,surname,othnames,gender,mstatus,DATE_FORMAT(dofbirth,'%d/%m/%Y') as dofbirth,branch, nrank,nrank,DATE_FORMAT(dofemp,'%d/%m/%Y') as dofemp,DATE_FORMAT(confdate,'%d/%m/%Y') as confdate,emptype, dept,sstatus,superv,dept,sstate, (SELECT CONCAT(saddr1,' ', saddr2,' ', saddr3) as address from hmrs_contact where staffid ='$this->userid' ) as contact,(SELECT semail from hmrs_contact where staffid ='$this->userid') as emails, (SELECT conemail from hmrs_contact where staffid ='$this->userid') as cemails, (SELECT sgsm from hmrs_contact where staffid = '$this->userid') as gsm, (SELECT fname from hmrs_uploads where (staffid = '$this->userid')  and (docclass ='PHO')) as fname FROM `hmrs_persdet` where staffid = '$this->userid' ";
```

</details>

<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
 
 


 
 
