# saikira
For testing Github to Confluence
  
// In `/application/library/pdf.php`:

<?php if (!defined('BASEPATH')) exit('No direct script access allowed');
 
class pdf {
    
    function pdf()
    {
        $CI = & get_instance();
        log_message('Debug', 'mPDF class is loaded.');
    }
 
    function load($params=NULL)
    {
        include_once APPPATH.'/third_party/mpdf/mpdf.php';
         
        if ($params == NULL)
        {
          // check the number of parameters here: http://mpdf1.com/manual/index.php?tid=184
          $params = array("en-GB-x", "A4", "", "", 10, 10, 10, 10, 6, 3, NULL);         
        } Test


Testimgn.,kjnmkmklsnc kjebv

    function load($params=NULL)
    {
       
SAIKIRAN-1
         
