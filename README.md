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

<?php echo jstrftime('%Y/%m/%d')?>
<?php echo gregorian_to_jalali(2017,03,21,'/');?>

Contact info
============
- Email:Pooya_parsa_dadashi{in}yahoo.com
- website: http://DatamWeb.ir/
- mobile : +989118847648
