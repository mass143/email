<? php
$to = ‘nobody@example.com’;
$subject = ‘the subject’;
$message = ‘hello’;
$headers = ‘from: nobody@example.com’. “\r\n”.‘Reply-To: nobody@example.com’.”\r\n”.‘X-Mailer: PHP/’ .phpversion ();
Mail ($to, $subject, $message, $headers);
?>
