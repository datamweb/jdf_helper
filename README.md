[![StyleCI](https://styleci.io/repos/80719967/shield?branch=analysis-8Qjo1P)](https://styleci.io/repos/80719967)
# CodeIgniter jdf_helper
Hijri_Shamsi,Solar(Jalali) Date and Time Helper for CodeIgniter

#Requirements
CodeIgniter should be configured to load `jdf_helper` automatically.

#Installation
=============
Just ...

- 1.copy `jdf_helper.php` into the `applications/helpers` directory.
- 2. Autoload the helper in `application/config/autoload.php` or load it in needed controllers with `$this->load->helper('jdf');`.

Enjoy now.

Usage
=====
For example, typing in the view file.

- echo jstrftime('%Y/%m/%d');
- echo gregorian_to_jalali(2017,03,21,'/');
- ```php
  $created_at = '2024-03-26 03:23:32';
  jdate('Y-m-d H:i:s',strtotime($created_at)); //۱۴۰۳-۰۱-۰۷ ۰۳:۲۳:۳۲
  
  ```

Contact info
============
- Email:Pooya_parsa_dadashi{in}yahoo.com
- website: http://DatamWeb.ir/
