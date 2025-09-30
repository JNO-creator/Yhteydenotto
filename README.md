<!-- Contact & Map Section -->
<section style="padding: 40px; background-color: #f9f9f9;" id="Otayhteytta">
  <h2 style="text-align:center; color: #0e194d;">Ota Yhteyttä</h2>

  <div style="display: flex; flex-wrap: wrap; justify-content: space-around; gap: 30px; margin-top: 30px;">

    <!-- Contact Form -->
    <form style="flex: 1 1 300px; max-width: 500px;" method="post" action="#">
      <label for="name">Nimi:</label><br>
      <input type="text" id="name" name="name" required style="width:100%; padding: 10px; margin-bottom: 10px;"><br>

      <label for="email">Sähköposti:</label><br>
      <input type="email" id="email" name="email" required style="width:100%; padding: 10px; margin-bottom: 10px;"><br>

      <label for="message">Viesti:</label><br>
      <textarea id="message" name="message" rows="5" required style="width:100%; padding: 10px; margin-bottom: 10px;"></textarea><br>

      <button type="submit" style="background-color:#0e194d; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer;">
        Lähetä
      </button>
    </form>

    <!-- Embedded Google Map -->
    <div style="flex: 1 1 300px; max-width: 500px;">
