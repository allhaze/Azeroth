## Hello
function encrypt($username, $password)
{
  $password = sha1(strtoupper($username) . ":" . strtoupper($password));
    $password = strtoupper($password);
      return $password;
}
