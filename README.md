<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NCC Enrollment Portal - MODERN COLLEGE PUNE</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body, html { font-family: Arial, sans-serif; background-color: #001f5b; color: #fff; }

    header { background-color: #001f5b; padding: 20px; }
    .header-container {
      display: flex; justify-content: space-between;
      align-items: center; flex-wrap: wrap;
    }
    .logo-left, .logo-right { height: 90px; width: auto; max-width: 100%; }
    .college-info {
      text-align: center; flex: 1; min-width: 250px;
      margin: 10px;
    }
    .college-info .subhead { color: #f7941d; font-style: italic; font-size: 18px; }
    .college-info .mainhead { font-size: 22px; font-weight: bold; color: #fff; }
    .college-info .address { font-size: 15px; color: #ccc; }

    nav ul {
      display: flex; justify-content: center;
      flex-wrap: wrap; list-style: none;
      background-color: #000e3d; padding: 10px 0;
    }
    nav ul li { margin: 0 15px; }
    nav ul li a {
      color: white; text-decoration: none;
      font-weight: bold; font-size: 16px;
    }
    nav ul li a:hover { color: #ffc72c; }

    .ticker {
      background-color: #0056a3; padding: 10px;
      overflow: hidden; white-space: nowrap; font-weight: bold;
    }
    .ticker span {
      display: inline-block; animation: scrollText 15s linear infinite; color: yellow;
    }
    @keyframes scrollText {
      from { transform: translateX(100%); }
      to { transform: translateX(-100%); }
    }

    #hero {
      height: 511px; background-size: cover;
      background-position: center; transition: background-image 1s ease-in-out;
      display: flex; flex-direction: column;
      justify-content: flex-end; align-items: center;
      text-align: center; padding: 20px;
    }
    #hero-content {
      background: rgba(0, 0, 0, 0.5);
      padding: 20px; border-radius: 10px;
    }
    #hero h2 { font-size: 28px; color: #fff; }
    #hero p { font-size: 16px; margin-top: 10px; }
    .cta-button {
      display: inline-block; margin-top: 15px;
      padding: 10px 20px; background-color: #ffc72c;
      color: #001f5b; border: none;
      border-radius: 5px; font-weight: bold;
      text-decoration: none;
    }

    
    section {
      padding: 30px 20px;
      background-color: #002f75;
      margin: 20px 0;
      border-radius: 10px;
    }
    section h3 {
      font-size: 24px; margin-bottom: 15px; color: #ffc72c;
    }
    section p, section ul {
      font-size: 15px; line-height: 1.6;
    }

    form {
      background: #003f99; padding: 20px;
      border-radius: 10px;
    }
    form input, form textarea, form select {
      width: 100%; padding: 10px;
      margin-bottom: 15px; border: none;
      border-radius: 5px;
      font-size: 14px;
    }
    form button {
      padding: 10px 20px; background-color: #ffc72c;
      color: #001f5b; border: none;
      border-radius: 5px; font-weight: bold;
      cursor: pointer; width: 100%;
    }

    @media screen and (max-width: 768px) {
      .header-container { flex-direction: column; text-align: center; }
      .logo-left, .logo-right { margin: 10px 0; }
      nav ul { flex-direction: column; }
      nav ul li { margin: 10px 0; }
      .cta-button { width: 100%; font-size: 16px; }
      #hero h2 { font-size: 22px; }
      #hero p { font-size: 14px; }
    }
  </style>

  <link rel="stylesheet" type="text/css" href="6.css">
</head>
<body>

  <header>
    <div class="header-container">
      <img src="3.png" alt="College Logo" class="logo-left" />
      <div class="college-info">
        <div class="subhead">Progressive Education Society’s</div>
        <div class="mainhead">Modern College of Arts, Science and Commerce (Autonomous)</div>
        <div class="address">Shivajinagar, Pune - 411005</div>
      </div>
      <img src="LOGO.jpg" alt="NCC Logo" class="logo-right" />
    </div>
    <nav>
      <ul>
        <li><a href="#about">About NCC</a></li>
        <li><a href="#eligibility">Eligibility</a></li>
        <li><a href="#enrollment">Enrollment</a></li>
        <li><a href="#activities">Activities</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <div class="ticker">
    <span>📢 NCC 2025 Enrollment is now open! | Physical verification starts July 10 | Upload documents before June 30.</span>
  </div>

  <section id="hero">
    <div id="hero-content">
      <h2>Let's salute the nation</h2>
      <p>Join NCC and serve the nation with honor and discipline.</p>
      
    </div>
  </section>
<a href="#form" class="cta-button">Apply Now</a>
  <section id="about">
    <h3>About NCC</h3>
    <p>The National Cadet Corps (NCC) is a youth development movement that instills discipline, leadership, and service values in students. NCC aims to develop character, comradeship, and leadership among youth and encourage them to become responsible citizens of India.</p>
    <p>At P.E.S. Modern College of Arts, Science and Commerce we are proud to be affiliated with the 36 Maharashtra Battalion-Army Wing. The battalion actively engages cadets in a transformative journey that builds confidence, responsibility and a deep sense of patriotism.</p>
  </section>



 <section id="benefits">
    <h3>Benefits</h3>
    <ul>
      <li>Career Opportunities:  
NCC "C" certificate holders can gain access to the Services Selection Board (SSB) for direct entry into the Indian Army, Navy, and Air Force. They also receive bonus marks in recruitment for paramilitary forces like BSF, CISF, and CRPF.</li>
      <li>Enhanced Personal Development:
NCC training cultivates valuable qualities like selflessness, honesty, discipline, and leadership, which are beneficial in various aspects of life. </li>
      <li>Basic Military Training:
NCC provides basic military training, developing an understanding of the Indian Armed Forces (Army, Navy, Air Force). </li>
    
    </ul>
  </section>

  <section id="eligibility">
    <h3>Eligibility</h3>
    <ul>
      <li>Must be a student of Modern College Pune.</li>
      <li>Age between 13 to 26 years.</li>
      <li>Physically fit and medically sound.</li>
      <li>Willing to participate in training camps and activities.</li>
    </ul>
  </section>



  <section id="enrollment">
  <h3>Enrollment Process</h3>
  <p>Interested students can apply online through the NCC Enrollment Portal. After application, students must attend physical verification and document submission sessions at the college.</p>
  <lu>
    <li>STEP 1:APPLY ONLINE</li>
    <li>STEP 2:DOCUMENTS (ADDHAR CARD, FEE RECEIPT, IF ANY ACHIEVEMENTS</li>
    <li>STEP 3
PHYSICAL TEST</li>
    <li>STEP 4
MEDICAL CERTIFICATE</li>
    <li>STEP 5
WRITTEN EXAM (50 MARKS)</li>

<li>STEP 6
INTERVIEW
</li>


  </lu>

</section>


  







  <section id="activities">
    <h3>Activities</h3>
    <ul>
      <li>Drill training and parades</li>
      <li>Social service and community outreach</li>
      <li>Adventure camps and trekking</li>
      <li>Annual Training Camp (ATC)</li>
      <li>Republic Day and Independence Day parades</li>
    </ul>
  </section>

<section id="contact">
  <h3>Contact Us</h3>
  <p><strong>NCC Office, Modern College Pune</strong></p>

  <marquee behavior="scroll" direction="left" scrollamount="5" style="color: #ffc72c; font-weight: bold;">
    If you have any query, feel free to contact us via Gmail: moderncollegearmywing@gmail.com
  </marquee>

  <p>Email: <a href="moderncollegearmywing@gmail.com" style="color: #ffc72c; text-decoration: underline;">moderncollegearmywing@gmail.com</a></p>
  <p>Phone: +91-12345-67890</p>
</section>
>

  <section id="form">
    <h3>Enrollment Form</h3>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Full Name" required />
     
      <input type="tel" name="phone" placeholder="Phone Number" required />
      
      <select name="gender" required>
        <option value="">Select Gender</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
      <textarea name="reason" rows="4" placeholder="Why do you want to join NCC?" required></textarea>
      

      <div style="background-color: #ffe4b3; color: #8b0000; padding: 15px; border-radius: 8px; margin-top: 20px; font-weight: bold;">
  ⚠️ Important: You must select <u>at least one wing</u> – Army or Navy. If none is selected, your enrollment will be <u>marked as pending.</u>And fill the form.
</div>


  <div style="display: flex; justify-content: space-between; gap: 66px; margin-top: 20px; text-align: center;">
  
  <!-- Include this CSS in your <style> section or CSS file -->
<style>
  .cta-button {
    display: inline-block;
    padding: 15px 91px;
    background-color: #ffc72c;
    color: #001f5b;
    border: none;
    border-radius: 9px;
    font-weight: bold;
    text-decoration: none;
    transition: background-color 0.3s ease;
    cursor: pointer;
  }

  .cta-button:hover {
    background-color: #ffdb6e;
  }

  .blink {
    animation: blink-animation 0.4s linear 2;
  }

  @keyframes blink-animation {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }

  @media (max-width: 768px) {
    .wing-buttons {
      flex-direction: column;
    }
  }
</style>

<!-- HTML for the buttons -->
<div class="wing-buttons" style="display: flex; justify-content: space-between; gap: 20px; margin-top: 20px; text-align: center; flex-wrap: wrap;">


  <!-- NAVY Wing Block (Left Side) -->
  <div style="flex: 1; min-width: 150px;">
  <h3 style="margin-bottom: 3px;">3 MAHARASHTRA NAVAL UNIT</h3>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLSdtEb70LGTXjPxLwsUrJekqx0ONRE493NbesxS6qhKbWkqJCQ/viewform?usp=header" target="_blank" class="cta-button" onclick="blinkEffect(this)">NAVY WING</a>
</div>


  <!-- ARMY Wing Block (Right Side) -->
  <div style="flex: 1; min-width: 150px;">
  <h3 style="margin-bottom: 3px;">36 MAHARASHTRA BATTALION</h3>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLSeYwVoD2bELvAVDl7OA6PMRjRs8UAVzHBDWLr0VumIQbZiTpA/viewform?usp=dialog" target="_blank" class="cta-button" onclick="blinkEffect(this)">ARMY WING</a>
</div>

<button type="submit">Submit Application</button>

<!-- JavaScript to add blink effect -->
<script>
  function blinkEffect(element) {
    element.classList.add('blink');
    setTimeout(() => {
      element.classList.remove('blink');
    }, 80); // Remove the class after 800ms (enough for 2 blinks)
  }
</script>


</div>


    












  </div>
    </form>
  </section>

  <script>
    const images = ['bg.png', 'bg2.jpg', 'bg3.jpg', 'bg4.jpg', 'bg5.jpg', 'bg6.jpg'];
    let currentIndex = 0;
    const heroSection = document.getElementById('hero');
    function changeBackground() {
      heroSection.style.backgroundImage = `url('${images[currentIndex]}')`;
      currentIndex = (currentIndex + 1) % images.length;
    }
    changeBackground();
    setInterval(changeBackground, 5000);
  </script>
   </script>


   <script>
  // Show modal after 5 seconds
  setTimeout(() => {
    document.getElementById('popup-modal').style.display = 'flex';
  }, 5000);

  // Close modal function
  function closeModal() {
    document.getElementById('popup-modal').style.display = 'none';
  }
</script>









  <footer style="background-color: #000e3d; padding: 20px; text-align: center; color: #ffc72c; font-size: 14px;">
    📅 <strong>Note:</strong> Enrollment deadline is <strong>June 30</strong>. Physical verification starts <strong>July 10</strong>. Stay tuned for further updates.
  </footer>

  <!-- Pop-up Modal -->
<div id="popup-modal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background-color:rgba(0,0,0,0.6); z-index:1000; justify-content:center; align-items:center;">
  <div style="background:#003f99; padding:30px; border-radius:10px; max-width:90%; width:400px; text-align:center; color:#fff;">
    <h3 style="color: #ffc72c;">Stay Updated!</h3>
    <p>Want to get the latest updates on NCC enrollment dates?</p>
    <p>📧 Connect with us at <strong> moderncollegearmywing@gmail.com  </strong></p>
    <button onclick="closeModal()" style="margin-top:15px; padding:10px 20px; background-color:#ffc72c; color:#001f5b; border:none; border-radius:5px; font-weight:bold;">Close</button>
  </div>
</div>


</body>
</html>

