<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Second Assignment</title>
</head>
<body>
    <style>
        table {
          border-collapse: collapse;
        }
      </style>
    <ol type="I">
        <li>Orange</li>
        <li>Banana</li>
        <li>Mango</li>
    </ol>

    <img src="pexels-esranurkalay-31624413.jpg" alt="Beautiful flowers">

    <video width="640" height="360" controls>
        <source src="/12927912_1080_1920_25fps.mp4" type="video/mp4">  
        Your browser does not support the video tag.
    </video>
    <audio controls>
        <source src="/3946077-uhd_4096_2160_25fps.mp4" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <table border="1" cellpadding="10">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Emails</th>
            </tr>
        </thead>
        
        <tbody>
            <tr>
                <td>Samantha</td>
                <td>210 Bold Street Centurion</td>
                <td>0822643345</td>
                <td>samanthaocean@gmail.com</td>
            </tr>

            <tr>
                <td>Robert</td>
                <td>290  Edenvale Street Pretoria</td>
                <td>0784744367</td>
                <td>robertsmith@gmail.com</td>
            </tr>

            <tr>
                <td>Hope</td>
                <td>1567 Mandela Street Burgersfort</td>
                <td>0817669434</td>
                <td>hopemomo@gmail.com</td>
            </tr>

            <tr>
                <td>Modiegi</td>
                <td>891 River lakes Lydenburg</td>
                <td>0637713662</td>
                <td>modiegisparks@gmail.com</td>
            </tr>

            <tr>
                <td>David</td>
                <td>440 Lions river Polokwane</td>
                <td>0836733616</td>
                <td>davidlawrence@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <br>

    <form action="">
        <label for="name">Name:</label>
        <input type="text" name="name" id="name" required> <br>
        <label for="email">Email</label>
        <input type="email" name="email" id="email"> <br>
        <label for="password">Password</label>
        <input type="password" name="password" id="password"> <br>
        <label for="dob">Date of Birth:</label>
        <input type="date" name="dob" id="dob" required> <br>

        <label for="chooseFruit">Choose fruit</label>
        <select name="fruit" id="fruit">
            <option value="Orange">Orange</option>
            <option value="Banana">Banana</option>
            <option value="Peach">Peach</option>
        </select> <br>

        <label for="chooseGender">Choose gender</label> <br>

        <label for="female">Female</label>
        <input type="radio" name="gender" id="female" value="female">

        <label for="male">Male</label>
        <input type="radio" name="gender" id="male" value="male">

        <label for="other">Other</label>
        <input type="radio" name="gender" id="other" value="other"> <br>

        <label for="Hobbies">Hobbies</label> <br>

        <label for="martialArts">Marial Arts</label>
        <input type="checkbox" name="martialArts" id="martialArts"> <br>

        <label for="Soccer">Soccer</label>
        <input type="checkbox" name="soccer" id="soccer"> <br>

        <label for="netball">Netball</label>
        <input type="checkbox" name="netball" id="netball">
    </form>
</body>
</html>
