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
  <ol>
  <li>
  <i><a href="https://sweetalert2.github.io/"> Make awesome alerts for Web projects</a></i></li>
 <li> <i><a href="https://www.w3schools.com/TAGS/att_input_pattern.asp"> Check for Regular Expressions using HTML</a></i></li>
    
  </ol>
      
</details>
<details>
  <summary><h4>Javascript</h4></summary>
  <ol><li>
   Regex to Validate Nigerian Phone Numbers.
   
````
   var regex2    = /234\d{11}$/; //For Phone Numbers in International Format (234xxxxxxxxxx)
     var gsm       = '23436377723000';
     var verify = gsm.includes("+");
     if(!gsm.match(regex2) || (verify)){
       console.log("Invalid Phone Number Specified. \nEnter Right Digit either in International Format 234xxxxxxxxxx");
      
     }
   
     else{
       console.log('coollllll, working' + verify );
       }  
````
</li>
</ol>
</details>
<details>
  <summary><h4>PHP</h4></summary>
  <ol>
  <li><i><a href="https://twitter.com/dreywandowski/status/1346514361725186049/"> Autoload</a></i></li>
    <li><i><a href="https://twitter.com/dreywandowski/status/1346514361725186049/"> How to Deploy Laravel Project with Apache on Ubuntu</a></i></li>
     <li><i><a href="https://stackoverflow.com/questions/67576998/has-been-blocked-by-cors-policy-no-access-control-allow-origin/"> Fix CORS errors from PHP API</a></i><br>
     
       header("Access-Control-Allow-Origin: *");
       header("Content-Type: application/json; charset=UTF-8");
       header("Access-Control-Allow-Methods: POST, GET");
       header("Access-Control-Max-Age: 3600");
       header("Access-Control-Allow-Headers: Content-Type, Access-Control-Allow-Headers, Authorization, X-Requested-With");
  
   </ol>   
</details>

<details>
  <summary><h4>GIT</h4></summary>
  <ol>
  <li><i><a href="https://stackoverflow.com/questions/2643502/git-how-to-solve-permission-denied-publickey-error-when-using-git"> How to solve Permission denied (publickey) error when using Git?</a></i></li>
    <li><i><a href="https://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories-on-rebase"> How to Deploy Laravel Project with Apache on Ubuntu</a></i></li>
     <li><i><a href="https://stackoverflow.com/questions/161813/how-do-i-resolve-merge-conflicts-in-a-git-repository"> How do I resolve merge conflicts in a Git repository?</a></i><br>
     <li><i><a href="https://weblog.masukomi.org/2008/07/12/handling-and-avoiding-conflicts-in-git/"> Handling and Avoiding Conflicts in Git</a></i><br>
          
    
   </ol>   
</details>
<details>
  <summary><h4>Laravel</h4></summary>
  <ol>
   <li><i><a href="https://stackoverflow.com/questions/23411520/how-to-fix-error-laravel-log-could-not-be-opened/"> How to fix Error: laravel.log could not be opened?</a></i>
    
 
  <li><i><a href="https://stackoverflow.com/questions/60843137/laravel-sanctum-unauthenticated/"> Authenticating with Sanctum API not working</a><br>
  <a href="https://stackoverflow.com/questions/67698004/problem-with-laravel-sanctum-token-security-search-of-very-well-explained-tuto">Second Link</a></i>
  
  ````
  sudo -su root
  cd to the root of laravel project
  
  sudo chown -R Aduramimo:www-data storage
  sudo chown -R Aduramimo:www-data bootstrap/cache
       bootstrap/cache   
  chmod -R 775 storage 
  ``````
  </li>
  

  
  </ol>    
</details>
<details>
  <summary><h4>Linux/Apache/Webhosting</h4></summary>
  <ol>
  <li><i><a href="https://usefulangle.com/post/326/azure-install-linux-apache-mysql-php-phpmyadmin-lamp-stack-ubuntu-18-04/"> How to Install LAMP (Linux, Apache, MySql & PHP) on Azure with Ubuntu 18.04</a></i></li>
 <li><i><a href="https://askubuntu.com/questions/1029177/error-1698-28000-access-denied-for-user-rootlocalhost-at-ubuntu-18-04/"> ERROR 1698 (28000): Access denied for user 'root'@'localhost' at Ubuntu 18.04</a></i></li>
   <li><i><a href="https://stackoverflow.com/questions/55237257/mysql-validate-password-policy-unknown-system-variable/"> MySQL validate_password_policy unknown system variable</a></i></li>
   <li><i><a href="https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal/"> How do I navigate between directories in terminal?</a></i></li>
         <li><i><a href="https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-18-04-quickstart/"> How To Set Up Apache Virtual Hosts on Ubuntu 18.04 [Quickstart]</a></i></li>
         <li><i><a href="https://www.interserver.net/tips/kb/deploy-laravel-project-apache-ubuntu//"> How to Deploy Laravel Project with Apache on Ubuntu</a></i></li>
         <li><i><a href="https://blog.quickadminpanel.com/laravel-public-folder-how-to-configure-domains-for-in-apachenginx/"> Laravel /public Folder: How to Configure Domains for in Apache/Nginx</a></i></li>
          <li><i><a href="https://www.edureka.co/community/81090/chmod-changing-permissions-of-root-operation-not-permitted/"> Linux: chmod changing permissions of root Operation not permitted/ how to switch users</a></i></li>
           <li><i><a href="https://askubuntu.com/questions/629995/apache-not-able-to-restart/"> Apache not able to restart</a></i></li>
                                          
</ol>      
</details>
<details>
  <summary><h4>MySQL</h4></summary>
  
  <ol>

  
  <li><i><a href="https://stackoverflow.com/questions/43094726/your-password-does-not-satisfy-the-current-policy-requirements/">  Your password does not satisfy the current policy requirements</a></i></li>

  <li><i><a href="https://stackoverflow.com/questions/35368643/sql-error-1822-failed-to-add-the-foreign-key-constaint-missing-index-for-cons/">SQL Error 1822 : Failed to add the foreign key constaint. Missing index for constraint BUT the index EXISTS</a></i></li>

 
  <li>
  Left Outer Join:
  
  ````sql
                          SELECT hmrs_persdet.staffid, title,surname,othnames,gender,mstatus,DATE_FORMAT(dofbirth,'%d/%m/%Y') as dofbirth,branch, nrank,nrank,DATE_FORMAT(dofemp,'%d/%m/%Y') as dofemp,DATE_FORMAT(confdate,'%d/%m/%Y') as confdate,emptype, dept,sstatus,superv,dept,sstate, CONCAT(saddr1,' ', saddr2,' ', saddr3) as address , semail as emails, conemail  as cemails, sgsm  as gsm, fname, desig  FROM `hmrs_persdet`
                        
                                        LEFT JOIN hmrs_contact as contact
                        
                                        on hmrs_persdet.staffid = contact.staffid
                        
                                        LEFT JOIN hmrs_uploads as uploads
                                        on hmrs_persdet.staffid = uploads.staffid
                        
                                        WHERE (docclass ='PHO')
                        
                                        and $this->status";
````
</li>

<li>
 
 Subquery
   ```
   ``"SELECT staffid,title,surname,othnames,gender,mstatus,DATE_FORMAT(dofbirth,'%d/%m/%Y') as dofbirth,branch, nrank,nrank,DATE_FORMAT(dofemp,'%d/%m/%Y') as dofemp,DATE_FORMAT(confdate,'%d/%m/%Y') as confdate,emptype, dept,sstatus,superv,dept,sstate, (SELECT CONCAT(saddr1,' ', saddr2,' ', saddr3) as address from hmrs_contact where staffid ='$this->userid' ) as contact,(SELECT semail from hmrs_contact where staffid ='$this->userid') as emails, (SELECT conemail from hmrs_contact where staffid ='$this->userid') as cemails, (SELECT sgsm from hmrs_contact where staffid = '$this->userid') as gsm, (SELECT fname from hmrs_uploads where (staffid = '$this->userid')  and (docclass ='PHO')) as fname FROM `hmrs_persdet` where staffid = '$this->userid' ";
```
</li>


</ol>
</details>


 
 


 
 
