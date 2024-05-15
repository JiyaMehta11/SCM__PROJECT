<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

<h2>SCM_PROJECT</h2>

<table>
    <thead>
        <tr>
            <th>Sr No.</th>
            <th>Roll No.</th>
            <th>Name</th>
            <th>Commit</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>2310990703</td>
            <td>Jigyasa</td>
            <td>Upload Version 2,Readme and changes in files</td>
        </tr>
        <tr>
            <td>2</td>
            <td>2310990704</td>
            <td>Jiya</td>
            <td>Upload Version 1,commit changes in files</td>
        </tr>
        <tr>
            <td>3</td>
            <td>2310990705</td>
            <td>Kabir</td>
            <td>Upload Final Version and commit changes</td>
        </tr>
    </tbody>
</table>

</body>
</html>
