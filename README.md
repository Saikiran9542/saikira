# saikira
For testing Github to Confluence

/**
 * See: https://davidsimpson.me/2013/05/19/using-mpdf-with-codeigniter/
 * and: https://twitter.com/freddysidauruk/status/586366799861563392
 */
 
 
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
        
        
 * See: https://davidsimpson.me/2013/05/19/using-mpdf-with-codeigniter/
 * and: https://twitter.com/freddysidauruk/status/586366799861563392
 */
 
 
// In `/application/library/pdf.php`:

<?php if (!defined('BASEPATH')) exit('No direct script access allowed');
 
