# uprak_informatika_9A
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Pendaftaran Lomba Lari</title>
    <style>
        body {
            font-family: Arial;
            background: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
        }
        button {
            width: 100%;
            padding: 10px;
            background: green;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: darkgreen;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Pendaftaran Lomba Lari</h2>
        <form action="halaman2.html">
            <label>Nama Lengkap:</label>
            <input type="text" required>

            <label>Umur:</label>
            <input type="number" required>

            <label>Jenis Kelamin:</label>
            <select required>
                <option value="">Pilih</option>
                <option>Laki-laki</option>
                <option>Perempuan</option>
            </select>

            <label>No HP:</label>
            <input type="tel" required>

            <button type="submit">Selanjutnya</button>
        </form>
    </div>
</body>
</html>
