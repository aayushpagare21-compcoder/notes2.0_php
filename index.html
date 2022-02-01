<!-- PHP SCRIPT #1 -->
<?php

//Connect to Database 
$server = "localhost";
$user = "root";
$password = "";
$database = "dbnotes";

$con = mysqli_connect($server, $user, $password, $database);


//DELETE FUNCTION
if (isset($_GET['delete'])) {
    $sno = $_GET['delete'];
    $sqld = "DELETE FROM `notes_db` WHERE `sno` = '$sno'";
    $resd = mysqli_query($con, $sqld);
}

//CREATE AND UPDATE FUNCTION
$insert_alert = false;
$update = false;
$delete = false;
if ($_SERVER['REQUEST_METHOD'] == 'POST') {

    if (isset($_POST['snoEdit'])) {
        $s = $_POST['snoEdit'];
        $t = $_POST['editTitle'];
        $d = $_POST['editDescription'];

        $sqlu = "UPDATE `notes_db` SET `description` = '$d' WHERE `notes_db`.`sno` = $s AND `notes_db`.`title` = '$t'";


        $resu = mysqli_query($con, $sqlu);

        $update = true;

        // echo var_dump($resu); 

    } else {
        //else create 
        $title = $_POST['title'];
        $description = $_POST['description'];

        $sqlc = "INSERT INTO `notes_db` (`title`, `description`) VALUES ('$title', '$description')";
        $resc = mysqli_query($con, $sqlc);

        if ($resc) {
            $insert_alert = true;
        }
    }
}
?>

<!-- MARKUP -->

<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="//cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <!-- google fonts  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+2&display=swap" rel="stylesheet">  

    <!-- css  -->
    <style> 
        body { 
            font-family: 'Baloo 2', cursive;
        } 
        .container { 
            border: 2px solid black; 
            border-radius: 1rem; 
            padding : 2rem;
        }  
        img { 
            height: 50px; 
            width: 80px; 
            border-radius: 1rem;
        } 
    </style>


    <!-- Table's CSS AND JAVASCRIPT AND JQUERY-->
    <link rel="stylesheet" href="//cdn.datatables.net/1.11.4/css/jquery.dataTables.min.css">
    <title>Notes 2.0</title>

    <script src="https://code.jquery.com/jquery-3.6.0.js" integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>

    <script src="//cdn.datatables.net/1.11.4/js/jquery.dataTables.min.js"></script>

    <script>
        $(document).ready(function() {
            $('#myTable').DataTable();
        });
    </script>

</head>

<body>

    <!-- EDIT MODAL -->
    <!-- Button trigger modal -->
    <!-- <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#editModal">
        Edit Modal
    </button> -->

    <!-- Modal -->
    <div class="modal fade" id="editModal" tabindex="-1" aria-labelledby="editModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="editModalLabel">Modal title</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">

                    <form action="/notes_crud/index.php/" method="POST">
                        <input type="hidden" name="snoEdit" id="snoEdit">
                        <div class="mb-4">
                            <label for="editTitle" class="form-label">Edit Title</label>
                            <input type="text" class="form-control" id="editTitle" aria-describedby="emailHelp" name="editTitle">
                        </div>

                        <div class="mb-4">
                            <label for="editDescription" class="form-label">Edit Description</label>
                            <textarea class="form-control" placeholder="Write Your Description Here" id="editDescription" name="editDescription" style="height: 100px"></textarea>

                            <!-- <label for="floatingTextarea2">Description</label> -->
                        </div>

                        <button type="submit" class="btn btn-primary">Update Note</button>
                    </form>

                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">Save changes</button>
                </div>
            </div>
        </div>
    </div>

    <!-- <h1>Hello, world!</h1> -->

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->


    <!-- _________________________________________________________________________________________________ -->
    <!-- NAVIGATION BAR -->

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img src="/notes_crud/new-php-logo.svg" alt="" srcset=""></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact Us</a>
                    </li>

                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search Note" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>


    <!-- ALERT BOXES -->
    <?php
    if ($insert_alert) {
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!</strong> Note Added.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    }
    ?>
    <?php
    if ($delete) {
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!</strong> Note Deleted.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    }
    ?>
    <?php
    if ($update) {
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!</strong> Note Updated.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    }
    ?>

    <!-- _____________________________________________________________________________________________________ -->
    <!-- form -->

    <div class="container my-4">
        <h2>Add A Note</h2>
        <hr>
        <br>
        <form action="/notes_crud/index.php/" method="POST">

            <div class="mb-4">
                <label for="title" class="form-label">Note Title</label>
                <input type="text" class="form-control" id="title" aria-describedby="emailHelp" name="title">
            </div>

            <div class="mb-4">
                <label for="description" class="form-label">Note Description</label>
                <textarea class="form-control" placeholder="Write Your Description Here" id="description" name="description" style="height: 100px"></textarea>

                <!-- <label for="floatingTextarea2">Description</label> -->
            </div>

            <button type="submit" class="btn btn-primary">Add Note</button>
        </form>

    </div>

    <!-- DISPLAY FUNCTION -->
    <div class="container my-5" id="notes">
        <br>
        <h2>Notes</h2>
        <hr><br>

        <table class="table" id="myTable">
            <thead>
                <tr>
                    <th scope="col">S.No</th>
                    <th scope="col">Title</th>
                    <th scope="col">Description</th>
                    <th scope="col">Time Saved</th>
                    <th scope="col">Actions</th>

                </tr>
            </thead>

            <tbody>
                <!-- Display ALL -  Query  -->
                <?php
                $sql = "SELECT * FROM `notes_db`";
                $res = mysqli_query($con, $sql);

                $sno = 0;

                while ($rows = mysqli_fetch_assoc($res)) {
                    $sno = $sno + 1;
                    echo "<tr>" .
                        "<td>" . $sno . "</td>" .
                        "<td>" . $rows['title'] . "</td>" .
                        "<td>" . $rows['description'] . "</td>" .
                        "<td>" . $rows['timestamp'] . "</td>" .
                        "<td> <button class='btn btn-sm btn-primary editModal' id=" . $rows['sno'] . "> Edit </button> <button class='btn btn-sm btn-primary deleteModal' id=" . $rows['sno'] . "> Delete</button>" .  "</td> 
                        </tr>";
                }
                ?>
            </tbody>
        </table>
    </div>
</body>

<!-- JAVASCRIPT FROM EDITING AND DELETING -->
<script>
    editModal = document.getElementsByClassName('editModal');
    Array.from(editModal).forEach((element) => {
        element.addEventListener('click', (e) => {
            tr = e.target.parentNode.parentNode;
            title = tr.getElementsByTagName('td')[1].innerText;
            description = tr.getElementsByTagName('td')[2].innerText;

            editTitle.value = title;
            editDescription.value = description;
            snoEdit.value = e.target.id;
            console.log(snoEdit.value);
            $('#editModal').modal('toggle');
        });
    });

    deleteModal = document.getElementsByClassName('deleteModal');
    Array.from(deleteModal).forEach((element) => {
        element.addEventListener('click', (e) => {
            sno = e.target.id;

            if (confirm("Do you really want to delete the note")) {
                console.log('Yes');
                window.location = `/notes_crud/index.php?delete=${sno}`;
            } else {
                console.log('NO');
            }
        });
    });
</script> 

<marquee behavior="slide" direction="left">First Php Project By Aayush</marquee>

</html>