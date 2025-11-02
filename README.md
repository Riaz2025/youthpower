<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YOUTH POWER - Empowering Youth Through Technology</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <style>
    .animate-slide-up {
      animation: slideUp 0.5s ease-out;
    }
    @keyframes slideUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    .hover-scale {
      transition: transform 0.3s ease;
    }
    .hover-scale:hover {
      transform: scale(1.05);
    }
    .gradient-bg {
      background: linear-gradient(135deg, #0056D2, #4FC3F7);
    }
  </style>
</head>
<body class="font-poppins bg-gray-100 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow sticky top-0 z-50">
    <nav class="container mx-auto px-4 py-4 flex justify-between items-center">
      <div class="text-2xl font-bold text-[#0056D2]">YOUTH POWER</div>
      <ul class="flex space-x-6">
        <li><a href="#home" class="hover:text-[#FF7A00]">Home</a></li>
        <li><a href="#about" class="hover:text-[#FF7A00]">About</a></li>
        <li><a href="#courses" class="hover:text-[#FF7A00]">Courses</a></li>
        <li><a href="#gallery" class="hover:text-[#FF7A00]">Gallery</a></li>
        <li><a href="#news" class="hover:text-[#FF7A00]">News & Events</a></li>
        <li><a href="#trainers" class="hover:text-[#FF7A00]">Trainers</a></li>
        <li><a href="#accreditation" class="hover:text-[#FF7A00]">Accreditation</a></li>
        <li><a href="#contact" class="hover:text-[#FF7A00]">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="gradient-bg text-white py-20">
    <div class="container mx-auto px-4 text-center">
      <h1 class="text-4xl md:text-5xl font-bold mb-4 animate-slide-up">
        Empowering Youth Through Technology & Skill Development
      </h1>
      <p class="text-lg md:text-xl mb-8 animate-slide-up">
        Join <BR> YOUTH POWER ICT & SKILL DEVELOPMENT INSTITUTE, BANGLADESH<BR> Where Learning Meets Innovation.
      </p>
      <div class="space-x-4">
        <a href="#apply" class="bg-[#FF7A00] text-white px-6 py-3 rounded-full hover:bg-orange-600 hover-scale">Apply for Admission</a>
        <a href="#courses" class="border-2 border-white text-white px-6 py-3 rounded-full hover:bg-white hover:text-[#0056D2] hover-scale">Explore Courses</a>
      </div>
    </div>
  </section>

  <!-- Quick Info Row -->
  <section class="bg-white py-10">
    <div class="container mx-auto px-4 grid grid-cols-1 md:grid-cols-4 gap-6 text-center">
      <div class="animate-slide-up">
        <h3 class="text-2xl font-bold text-[#0056D2]">50+</h3>
        <p>Courses Offered</p>
      </div>
      <div class="animate-slide-up">
        <h3 class="text-2xl font-bold text-[#0056D2]">10,000+</h3>
        <p>Students Trained</p>
      </div>
      <div class="animate-slide-up">
        <h3 class="text-2xl font-bold text-[#0056D2]">100+</h3>
        <p>Achievements</p>
      </div>
      <div class="animate-slide-up">
        <h3 class="text-2xl font-bold text-[#0056D2]">20+</h3>
        <p>Districts Covered</p>
      </div>
    </div>
  </section>

  <!-- Why Choose YOUTH POWER ISDI -->
  <section class="py-16 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Why Choose YOUTH POWER ISDI?</h2>
      <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Modern Computer Lab</h3>
          <p>State-of-the-art facilities for hands-on learning.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Certified Trainers</h3>
          <p>Expert instructors with industry experience.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Govt. Recognized Courses</h3>
          <p>Accredited programs for credibility.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Career Support</h3>
          <p>Guidance to kickstart your career.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us -->
  <section id="about" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">About Us</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div>
          <h3 class="text-xl font-semibold text-[#0056D2]">Mission</h3>
          <p> Build a digitally skilled generation for Smart Bangladesh.</p>
          <h3 class="text-xl font-semibold text-[#0056D2] mt-6">Vision</h3>
          <p>To be a leading ICT and vocational training institute in Bangladesh.</p>
          <h3 class="text-xl font-semibold text-[#0056D2] mt-6">Core Values</h3>
          <ul class="list-disc pl-5">
            <li>Integrity</li>
            <li>Innovation</li>
            <li>Empowerment</li>
            <li>Skill</li>
          </ul>
        </div>
        <div>
          <h3 class="text-xl font-semibold text-[#0056D2]">Message from Founder</h3>
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhHkuv1oGzGZHfSyCnSWdtR80DQdezo2nprCvZ-4H7j7hRj_iL69A_E5ThuRJqnsWktSrITSEPGMhxmPs_r2oBVpzMLl-6AncAwDP1uSv210t4NbPUTnJbl2uhM50gqo1k5tYK8MzfjZkXxsMZwTIKbNRSvd6CZWFCxylByYuHlICrNVtKAD56pOYPeI5GW/s320/facebook_profile-removebg-preview.png" alt="Founder" class="rounded-full my-4" height="20">
          <p>"At YPISDI, we believe in empowering youth with the skills to shape their future and contribute to a Smart Bangladesh." - Founder</p>
          <h3 class="text-xl font-semibold text-[#0056D2] mt-6">History & Achievements</h3>
          <p>Established in 2010, YPISDI has trained thousands of students, earning multiple awards for excellence in ICT education.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Courses -->
  <section id="courses" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Our Courses</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]"> Computer Oparation</h3>
          <p>Duration: 6 months <br>Schedule: Sat-Thu,  8AM-8PM<br>Fee: BDT 6,500<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]"> Frelanching & Digital Marketing </h3>
          <p>Duration: 4 months <br> Schedule: Sat-Thu,  8AM-8PM<br>Fee: BDT 12,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Electronics </h3>
          <p>Duration: 3 months <br> Schedule: Sat-Thu,  8AM-8PM,<br>Fee: BDT 5,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Beautification</h3>
          <p>Duration: 3 months<br>Schedule: Sat-Thu,  8AM-8PM <br>Fee: BDT 12,000 <br> Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Food Proccesing and Catering</h3>
          <p>Duration: 3 months<br>Schedule: Sat-Thu,  8AM-8PM<br>Fee: BDT 6,000<br> Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Spoken English</h3>
          <p>Duration: 3 months<br>Schedule: Fri-Sun, 2 PM-4 PM<br>Fee: BDT 4,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Programming & IOT </h3>
          <p>Duration: 12 months<br> Schedule: Sat-Thu,  8AM-8PM <br> Fee: BDT 15,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>


  	<div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Artificial Intelligence (AI)</h3>
          <p>Duration: 3 months<br> Schedule: Sat-Thu,  8AM-8PM <br> Fee: BDT 5,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>


	<div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">ICT (HSC) </h3>
          <p>Duration: 12 months<br> Schedule: Sat-Thu,  8AM-8PM <br> Fee: BDT 12,000<br>Certificate: Govt. Recognized</p>
          <a href="#apply" class="mt-4 inline-block bg-[#FF7A00] text-white px-4 py-2 rounded-full hover:bg-orange-600">Apply Now</a>
        </div>

      </div>
    </div>
  </section>
 <!---------------------------------------------------------------- Main Section end-------------------------------------------------------------------------- -->


  <!-- Gallery -->
  <section id="gallery" class="py-16 bg-white">

    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Gallery</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiZ7s4zs2NwK0bVo3PR9wXtySCzRbF5bOpMuWbIalales275t5OOadEGJX4SAEESyBYnKniZ4St43te3IDSN3vR7OPgmuYYRO92LPGaqzVhY-AZttTs9oYvy8h__rkmyebwZ4mQflbNycBPwsNeg7vqetpZ16BUBx9nCWtT5us3LRorj9HQ8MPeyT9xetdA/s4080/IMG_20250711_113223.jpg " alt="Class" class="rounded-lg hover-scale">
        <img src=" https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgycp2eKfsADsN-ntITMqiBiCk26R9UNU2-S83IN9gutkMiwihKZVW5EU4ZRmsxlxhPHvHlRj8YyhUo339Pi4Dh2aL5sYjT1D8lPXq8587sTZF_WAczhRNSmC0JvYDf0GvjF3cDRw6UDmMrUuzDSEwhjvvQPkafApMPtHjBrf5MaQ8dPz8SAKdRQnAm3y8G/s1280/%E0%A6%AA%E0%A7%8D%E0%A6%B0%E0%A6%AF%E0%A7%81%E0%A6%95%E0%A7%8D%E0%A6%A4%E0%A6%BF%20%E0%A6%AC%E0%A6%BF%E0%A6%B7%E0%A7%9F%E0%A6%95%20%E0%A6%95%E0%A7%8D%E0%A6%B2%E0%A6%BE%E0%A6%B8%E0%A7%A7.jpg" alt="Class" class="rounded-lg hover-scale">
	<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjJeZ6gp47Ta7VoZ0CO_RN5UlmJHl6v_kwkcc70CU5olWyZUuhakaueUQA2kMv0btAO-gUi89mDBzusNFsUFSQkwfJhEJ5hMm2Cdl3dUmJ0bhYojpqtsrt6MelVGaGbZhpM076yIIuCaRqxn-b3-u5zdyLXcmqAOke-dqpb6nc_DTjrhPoZr1dEBR5BQrj3/s1280/%E0%A6%B8%E0%A7%81%E0%A6%95%E0%A6%A6%E0%A7%87%E0%A6%AC%20%E0%A6%B8%E0%A7%8D%E0%A6%95%E0%A7%81%E0%A6%B2.jpeg" alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
	<img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
	<img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
	<img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
	<img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
        <img src=" " alt="Class" class="rounded-lg hover-scale">
	<img src=" " alt="Class" class="rounded-lg hover-scale">



      </div>
    </div>
  </section>


<!-- Gallery -->
  <section id="gallery" class="py-16 bg-white">

    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Video</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <video src="assets/testimonial.mp4" controls class="rounded-lg hover-scale"></video>
      </div>
    </div>
  </section>

  <!-- News & Events -->
  <section id="news" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">News & Events</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">ICT Workshop 2025</h3>
          <p>Join our upcoming workshop on advanced ICT skills!</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Certificate Distribution</h3>
          <p>Celebrating our latest batch of graduates!</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <h3 class="text-xl font-semibold text-[#0056D2]">Admission Open</h3>
          <p>Enroll now for our Winter 2025 courses!</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Trainers -->
  <section id="trainers" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Our Trainers</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow hover-scale">
          <img src="assets/trainer1.jpg" alt="Trainer" class="rounded-full mb-4">
          <h3 class="text-xl font-semibold text-[#0056D2]">John Doe</h3>
          <p>Web Development Expert</p>
          <div class="flex space-x-2 mt-2">
            <a href="#" class="text-[#0056D2]"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="#" class="text-[#0056D2]"><i class="fab fa-twitter"></i> Twitter</a>
          </div>
        </div>
        <!-- Add more trainers as needed -->
      </div>
    </div>
  </section>

  <!-- Accreditation -->
  <section id="accreditation" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Accreditation</h2>
      <div class="flex justify-center space-x-6">
        <img src="assets/nsda.jpg" alt="NSDA" class="hover-scale">
        <img src="assets/dyd.jpg" alt="DYD" class="hover-scale">
      </div>
      <p class="text-center mt-6">Trade License: 12345 | Registration: ABC-2025</p>
      <a href="assets/certificate.pdf" class="block text-center mt-4 text-[#0056D2] hover:text-[#FF7A00]" download>Download Certificate (PDF)</a>
    </div>
  </section>

  <!-- Contact Us -->
  <section id="contact" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-[#0056D2] mb-10 animate-slide-up">Contact Us</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div>
          <p><strong>Address:</strong> Daulatkhan, Bhola, Bangladesh</p>
          <p><strong>Phone:</strong> 01889289718</p>
          <p><strong>Email:</strong> info@ypisdi.org</p>
          <iframe class="w-full h-64 mt-4 rounded-lg" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3680.733563305985!2d90.7351863154046!3d22.606675985167543!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3754e8f6896e6b73%3A0xbeca5a9e8c39d6b9!2sDaulatkhan%2C%20Bhola%2C%20Bangladesh!5e0!3m2!1sen!2sus!4v1698067200000" frameborder="0" allowfullscreen></iframe>
        </div>
        <div>
          <div class="bg-gray-100 p-6 rounded-lg">
            <h3 class="text-xl font-semibold text-[#0056D2] mb-4">Send Us a Message</h3>
            <input type="text" placeholder="Name" class="w-full p-3 mb-4 rounded-lg border">
            <input type="email" placeholder="Email" class="w-full p-3 mb-4 rounded-lg border">
            <textarea placeholder="Message" class="w-full p-3 mb-4 rounded-lg border" rows="5"></textarea>
            <button class="bg-[#FF7A00] text-white px-6 py-3 rounded-full hover:bg-orange-600">Submit</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-[#0056D2] text-white py-10">
    <div class="container mx-auto px-4 text-center">
      <img src="assets/logo-white.png" alt="YPISDI Logo" class="mx-auto mb-4 w-24">
      <div class="flex justify-center space-x-6 mb-4">
        <a href="#home" class="hover:text-[#FF7A00]">Home</a>
        <a href="#about" class="hover:text-[#FF7A00]">About</a>
        <a href="#courses" class="hover:text-[#FF7A00]">Courses</a>
        <a href="#contact" class="hover:text-[#FF7A00]">Contact</a>
      </div>
      <div class="flex justify-center space-x-4 mb-4">
        <a href="#" class="hover:text-[#FF7A00]"><i class="fab fa-facebook-f"></i></a>
        <a href="#" class="hover:text-[#FF7A00]"><i class="fab fa-twitter"></i></a>
        <a href="#" class="hover:text-[#FF7A00]"><i class="fab fa-linkedin-in"></i></a>
      </div>
      <p>© 2025 YPISDI, Bangladesh — All Rights Reserved.</p>
    </div>
  </footer>

  <script>
    // Smooth scroll for navigation links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>

