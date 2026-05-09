<!DOCTYPE html>
<html>

<head>
    <title>Pendaftaran Mahasiswa Baru</title>

    <style>
        body {
            font-family: Arial;
            background: #f2f2f2;
            margin: 20px;
        }

        .container {
            width: 95%;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table,
        th,
        td {
            border: 1px solid black;
        }

        th,
        td {
            padding: 8px;
            text-align: center;
        }

        input,
        textarea {
            padding: 5px;
            margin: 3px;
        }

        .form-table td {
            border: none;
            text-align: left;
        }

        button {
            padding: 10px 20px;
            background: blue;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <div class="container">

        <h2>INPUT PENDAFTARAN</h2>

        <form method="POST">

            <table class="form-table">

                <tr>
                    <td>JUMLAH INPUT DATA</td>
                    <td><input type="number" name="jumlah"></td>
                </tr>

                <tr>
                    <td>KODE PENDAFTARAN</td>
                    <td><input type="text" name="kode" required></td>
                </tr>

                <tr>
                    <td>NAMA PENDAFTAR</td>
                    <td><input type="text" name="nama" required></td>
                </tr>

                <tr>
                    <td>JENIS KELAMIN</td>
                    <td>
                        <input type="radio" name="jk" value="Laki-laki"> Laki-laki
                        <input type="radio" name="jk" value="Perempuan"> Perempuan
                    </td>
                </tr>

                <tr>
                    <td>TTL</td>
                    <td>
                        <input type="text" name="tempat" placeholder="Tempat Lahir">
                        <input type="date" name="tanggal">
                    </td>
                </tr>

                <tr>
                    <td>ASAL SEKOLAH</td>
                    <td><input type="text" name="sekolah"></td>
                </tr>

                <tr>
                    <td>PEKERJAAN ORTU</td>
                    <td>
                        <textarea name="ortu"></textarea>
                    </td>
                </tr>

                <tr>
                    <td>NILAI TES</td>
                    <td></td>
                </tr>

                <tr>
                    <td>MATEMATIKA</td>
                    <td><input type="number" name="mat"></td>
                </tr>

                <tr>
                    <td>BHS. INGGRIS</td>
                    <td><input type="number" name="inggris"></td>
                </tr>

                <tr>
                    <td>P. UMUM</td>
                    <td><input type="number" name="umum"></td>
                </tr>

                <tr>
                    <td></td>
                    <td>
                        <button type="submit" name="simpan">SIMPAN</button>
                        <button type="reset">RESET</button>
                    </td>
                </tr>

            </table>

        </form>

        <?php

        if (isset($_POST['simpan'])) {

            $jumlah = $_POST['jumlah'];
            $kode = $_POST['kode'];
            $nama = $_POST['nama'];
            $jk = $_POST['jk'];
            $tempat = $_POST['tempat'];
            $tanggal = $_POST['tanggal'];
            $sekolah = $_POST['sekolah'];
            $ortu = $_POST['ortu'];

            $mat = $_POST['mat'];
            $inggris = $_POST['inggris'];
            $umum = $_POST['umum'];

            // HITUNG RATA-RATA
            $rata = ($mat + $inggris + $umum) / 3;

            // KETERANGAN
            if ($rata >= 70) {
                $keterangan = "LULUS";
            } elseif ($rata >= 60) {
                $keterangan = "CADANGAN";
            } else {
                $keterangan = "TIDAK LULUS";
            }

            // MENENTUKAN TEMPAT TES
            $awal = strtoupper(substr($kode, 0, 1));

            if ($awal == "A") {
                $tempatTes = "Gedung A";
            } elseif ($awal == "B") {
                $tempatTes = "Gedung B";
            } elseif ($awal == "V") {
                $tempatTes = "Viktor";
            } else {
                $tempatTes = "Tidak Diketahui";
            }

            // AMBIL BULAN TES
            $bulanTes = substr($kode, -1);

            // HITUNG JUMLAH LULUS
            $jumlahLulus = 0;
            $jumlahTidak = 0;

            if ($keterangan == "LULUS") {
                $jumlahLulus = 1;
            } else {
                $jumlahTidak = 1;
            }

            ?>

            <h2>TABEL DATA</h2>

            <table>

                <tr>
                    <th>Kode Pendaftar</th>
                    <th>Nama Pendaftar</th>
                    <th>Tempat Lahir</th>
                    <th>JK</th>
                    <th>Tgl Lahir</th>
                    <th>Pek. Ortu</th>
                    <th>Tempat Tes</th>
                    <th>Bln Tes</th>
                    <th>MAT</th>
                    <th>INGG</th>
                    <th>UMUM</th>
                    <th>R.RATA</th>
                    <th>KETERANGAN</th>
                </tr>

                <tr>

                    <td><?php echo $kode; ?></td>
                    <td><?php echo $nama; ?></td>
                    <td><?php echo $tempat; ?></td>
                    <td><?php echo $jk; ?></td>
                    <td><?php echo $tanggal; ?></td>
                    <td><?php echo $ortu; ?></td>
                    <td><?php echo $tempatTes; ?></td>
                    <td><?php echo $bulanTes; ?></td>
                    <td><?php echo $mat; ?></td>
                    <td><?php echo $inggris; ?></td>
                    <td><?php echo $umum; ?></td>
                    <td><?php echo number_format($rata, 2); ?></td>
                    <td><?php echo $keterangan; ?></td>

                </tr>

                <tr>
                    <td colspan="13">
                        JUMLAH PENDAFTAR : <?php echo $jumlah; ?>
                    </td>
                </tr>

                <tr>
                    <td colspan="13">
                        JUMLAH PESERTA LULUS : <?php echo $jumlahLulus; ?>
                    </td>
                </tr>

                <tr>
                    <td colspan="13">
                        JUMLAH TIDAK PESERTA LULUS : <?php echo $jumlahTidak; ?>
                    </td>
                </tr>

            </table>

            <?php
        }
        ?>

    </div>

</body>

</html>