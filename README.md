Cookinator
==========

Simple cookie session store

Usage
=====

    require_once('Cookinator.php');
    $cookinator = new Cookinator();
    $cookinator->apple = 'holy cow';
    var_dump(isset($cookinator->apple));
    echo 'My Cookie is : '.$cookinator->apple;
