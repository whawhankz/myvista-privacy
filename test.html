<!DOCTYPE html>
<html>
<body>

<h1>The onclick Event</h1>

<?php
    echo "<iframe id='maps' height='95%' width='100%' frameborder='0' src=''></iframe>";
    echo "<text id='nama'></text>"
    //echo "<p id='maps'></p>";
?>
<table border="1">
    <tr>
        <td></td>><center>NO</center></th>
        <td></td>><center>Visitor</center></th>
        <td></td>><center>Regional</center></th>
        <td></td>><center>Lokasi</center></th>
        <td></td>><center></center></th>
    </tr>
<table border="1">

    <tbody>
    <?php
    include "conf/config.php";
        $tgl = date('Y-m-d');
        $query_nama = mysqli_query($link, "SELECT visitor, regional, COUNT(*) AS total, lokasi_visitor, koordinat_visitor FROM tb_visitor WHERE tgl_visit BETWEEN '$tgl 00:00:00' AND '$tgl 23:59:00'
            GROUP BY visitor LIMIT 10");
        if(mysqli_num_rows($query_nama) > 0) {
        $no = 1;
        while($hasil=mysqli_fetch_array($query_nama)) {
            echo "
            <td align='center'>$no.</td>
            <td>".strtoupper($hasil[0])."</td>
            <td>$hasil[regional]</td>
            <td>$hasil[koordinat_visitor]</td>
            <td align='center'>";?><button onclick="myFunction('<?= $hasil[4]?>','<?= $hasil[0]?>')" class='btn btn-outline-dark waves-effect waves-light'>Detail</button><?php echo "</td>
            </tr>
            "; 
            $no++;
        } 
    } else {
        echo "<td colspan=4>Data masih kosong.</td></tr>";
    }
    ?>

    <script>
    function myFunction(koordinat, visitor) {
        document.getElementById("maps").src = 'https://www.google.co.id/maps?f=q&source=s_q&hl=en&geocode=&q='+koordinat+'&z=14&output=embed';
        document.getElementById("nama").innerHTML = koordinat+' '+visitor;
    }

    </script>

    </tbody>
</table>
</table>


</body>
</html>
