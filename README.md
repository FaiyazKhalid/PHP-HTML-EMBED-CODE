# PHP-HTML-EMBED-CODE

How to embeed html code and text in php see below


$html = <<<HTML
<p><br /></p>
<form name="form" action="">
<input type="text" name="search" size="30" /> 
<input type="button" value="$buttonvalue" 
 onclick='window.location.assign(document.URL.substring(0,document.URL.indexOf("?")) + "?search=" + document.form.search.value.replace(/ /g,"%20"))' />
</form>
<!-- Please do not remove or change this link to the application's site. Others might like it too. -->

HTML;


