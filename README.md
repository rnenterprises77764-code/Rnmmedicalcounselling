# Rnmmedicalcounselling
Medical admission councellor webpage 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Firm Name</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
    header { background: #0f172a; color: #fff; padding: 20px; }
    section { padding: 20px; margin: 15px; background: #fff; border-radius: 8px; }
    h2 { color: #0f172a; }
    .packages { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 15px; }
    .card { border: 1px solid #ddd; padding: 15px; border-radius: 8px; }
    .card button { background: #0f172a; color: #fff; border: none; padding: 8px 12px; cursor: pointer; border-radius: 4px; }
    footer { background: #0f172a; color: #fff; padding: 15px; text-align: center; }
    a { color: #2563eb; text-decoration: none; margin-right: 10px; }
    input, select, textarea { width: 100%; padding: 8px; margin-top: 6px; margin-bottom: 12px; }
    button.submit { background: #16a34a; color: #fff; border: none; padding: 10px; width: 100%; }
  </style>
</head>
<body>

<header>
  <h1>Your Firm Name</h1>
  <p>Electrical | Training | Services</p>
</header>

<section>
  <h2>About Us</h2>
  <p>
    We provide professional electrical training and services. Our programs are designed
    for students and working professionals who want practical knowledge and certification.
  </p>
</section>

<section>
  <h2>Contact Details</h2>
  <p>📞 Phone: +91-XXXXXXXXXX</p>
  <p>📧 Email: yourfirm@email.com</p>
  <p>
    <a href="#">Instagram</a>
    <a href="#">Telegram</a>
    <a href="#">WhatsApp</a>
  </p>
</section>

<section>
  <h2>Our Packages</h2>
  <div class="packages">
    <div class="card"><h3>Package 1</h3><p>Basic Course</p><p>₹1,000</p></div>
    <div class="card"><h3>Package 2</h3><p>Standard Course</p><p>₹2,000</p></div>
    <div class="card"><h3>Package 3</h3><p>Advanced Course</p><p>₹3,000</p></div>
    <div class="card"><h3>Package 4</h3><p>Professional Course</p><p>₹5,000</p></div>
    <div class="card"><h3>Package 5</h3><p>Expert Course</p><p>₹8,000</p></div>
    <div class="card"><h3>Package 6</h3><p>Complete Bundle</p><p>₹10,000</p></div>
  </div>
</section>

<section>
  <h2>Student Information Form</h2>
  <form>
    <label>Full Name</label>
    <input type="text" required />

    <label>Mobile Number</label>
    <input type="tel" required />

    <label>Email</label>
    <input type="email" />

    <label>Select Package</label>
    <select required>
      <option value="">-- Select --</option>
      <option>Package 1 - ₹1,000</option>
      <option>Package 2 - ₹2,000</option>
      <option>Package 3 - ₹3,000</option>
      <option>Package 4 - ₹5,000</option>
      <option>Package 5 - ₹8,000</option>
      <option>Package 6 - ₹10,000</option>
    </select>

    <p><strong>Payment:</strong> (Razorpay / UPI / Payment Gateway to be integrated)</p>

    <button type="submit" class="submit">Submit & Pay</button>
  </form>
</section>

<section>
  <h2>Notifications</h2>
  <ul>
    <li>01 Jan: New batch starting from 10 Jan.</li>
    <li>02 Jan: Package 3 updated syllabus.</li>
  </ul>
  <p>(You can update 1–2 line notifications daily)</p>
</section>

<footer>
  <p>© 2025 Your Firm Name. All rights reserved.</p>
</footer>

</body>
</html>
