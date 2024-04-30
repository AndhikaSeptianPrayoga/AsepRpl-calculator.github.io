<?php
$hasil = '';
$input = '';

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    if (isset($_POST['input'])) {
        $input = $_POST['input'];
    }

    if (isset($_POST['num'])) {
        $input .= $_POST['num'];
    }

    if (isset($_POST['op'])) {
        setcookie('num', $input, time() + (86400 * 30), "/");
        setcookie('op', $_POST['op'], time() + (86400 * 30), "/");
        $input = '';
    }

    if (isset($_POST['equal'])) {
        if (isset($_COOKIE['num']) && is_numeric($_COOKIE['num']) && is_numeric($input)) {
            $num = $_COOKIE['num'];
            $operasi = $_COOKIE['op'];

            switch ($operasi) {
                case "+":
                    $hasil = $num + $input;
                    break;
                case "-":
                    $hasil = $num - $input;
                    break;
                case "*":
                    $hasil = $num * $input;
                    break;
                case "/":
                    if ($input != 0) {
                        $hasil = $num / $input;
                    } else {
                        $hasil = "Tidak dapat dibagi dengan nol!";
                    }
                    break;
                default:
                    $hasil = "Operasi tidak valid";
                    break;
            }
        } else {
            $hasil = "Operasi tidak valid";
        }
        $input = $hasil;
    }

    if (isset($_POST['clear'])) {
        setcookie('num', '', time() - 3600, "/");
        setcookie('op', '', time() - 3600, "/");
        $input = '';
        $hasil = '';
    }
}
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 70vh;
        }

        .calc {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 100%;
            max-width: 300px;
            zoom: 130%;
        }

        .maininput {
            width: 100%;
            box-sizing: border-box;
            border: 1px solid #ccc;
            padding: 10px;
            font-size: 24px;
            margin-bottom: 10px;
        }

        .button {
            width: 45px;
            height: 45px;
            font-size: 20px;
            margin: 5px;
            border: none;
            border-radius: 50%;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .numbtn {
            background-color: #e0e0e0;
        }

        .calbtn {
            background-color: orange;
            color: #fff;
        }

        .c {
            background-color: red;
            color: #fff;
        }

        .equal {
            background-color: green;
            color: #fff;
        }


        @media (max-width: 600px) {
            .calc {
                width: 100%;
            }

            .button {
                width: 40px;
                height: 40px;
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
<div class="calc">
    <form action="" method="post">
        <input type="text" class="maininput" name="input" value="<?= htmlspecialchars($input) ?>" readonly> <br>
        <input type="submit" class="button numbtn" name="num" value="7">
        <input type="submit" class="button numbtn" name="num" value="8">
        <input type="submit" class="button numbtn" name="num" value="9">
        <input type="submit" class="button calbtn" name="op" value="+"> <br>
        <input type="submit" class="button numbtn" name="num" value="4">
        <input type="submit" class="button numbtn" name="num" value="5">
        <input type="submit" class="button numbtn" name="num" value="6">
        <input type="submit" class="button calbtn" name="op" value="-"><br>
        <input type="submit" class="button numbtn" name="num" value="1">
        <input type="submit" class="button numbtn" name="num" value="2">
        <input type="submit" class="button numbtn" name="num" value="3">
        <input type="submit" class="button calbtn" name="op" value="*"><br>
        <button type="submit" class="button clear" name="clear" value="C">C</button>
        <input type="submit" class="button numbtn" name="num" value="0">
        <input type="submit" class="button equal" name="equal" value="=">
        <input type="submit" class="button calbtn" name="op" value="/">


    </form>
</div>
</body>
</html>