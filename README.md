<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>GIC Baggha-54 School</title>
  <link href="https://fonts.googleapis.com" rel="preconnect"/>
  <link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
  <link href="https://fonts.googleapis.com/css2?family=Public+Sans:wght@400;500;700;900&family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet"/>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <style type="text/tailwindcss">
    :root {
      --primary-color: #1173d4;
      --secondary-color: #e0efff;
      --background-color: #f8faff;
      --text-primary: #1a202c;
      --text-secondary: #4a5568;
      --accent-color: #1173d4;
    }
    body {
      font-family: 'Public Sans', 'Inter', sans-serif;
      background-color: var(--background-color);
      color: var(--text-primary);
    }
  </style>
</head>
<body class="bg-[var(--background-color)] text-[var(--text-primary)]">
<div class="relative flex size-full min-h-screen flex-col overflow-x-hidden">

<!-- Header -->
<header class="bg-white shadow-sm sticky top-0 z-50">
  <nav class="container mx-auto px-6 py-4 flex justify-between items-center max-w-7xl">
    <div class="flex items-center gap-3">
      <svg class="h-8 w-8 text-[var(--primary-color)]" fill="none" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
        <path clip-rule="evenodd" d="M24 18.4228L42 11.475V34.3663C42 34.7796 41.7457 35.1504 41.3601 35.2992L24 42V18.4228Z" fill="currentColor" fill-rule="evenodd"></path>
        <path clip-rule="evenodd" d="M24 8.18819L33.4123 11.574L24 15.2071L14.5877 11.574L24 8.18819ZM9 15.8487L21 20.4805V37.6263L9 32.9945V15.8487ZM27 37.6263V20.4805L39 15.8487V32.9945L27 37.6263ZM25.354 2.29885C24.4788 1.98402 23.5212 1.98402 22.646 2.29885L4.98454 8.65208C3.7939 9.08038 3 10.2097 3 11.475V34.3663C3 36.0196 4.01719 37.5026 5.55962 38.098L22.9197 44.7987C23.6149 45.0671 24.3851 45.0671 25.0803 44.7987L42.4404 38.098C43.9828 37.5026 45 36.0196 45 34.3663V11.475C45 10.2097 44.2061 9.08038 43.0155 8.65208L25.354 2.29885Z" fill="currentColor" fill-rule="evenodd"></path>
      </svg>
      <h1 class="text-xl font-bold text-[var(--text-primary)]">GIC Baggha-54</h1>
    </div>
    <div class="hidden md:flex items-center space-x-8">
      <a class="text-[var(--text-secondary)] hover:text-[var(--primary-color)] font-medium transition" href="#about">About Us</a>
      <a class="text-[var(--text-secondary)] hover:text-[var(--primary-color)] font-medium transition" href="#academics">Academics</a>
      <a class="text-[var(--text-secondary)] hover:text-[var(--primary-color)] font-medium transition" href="#admissions">Admissions</a>
      <a class="text-[var(--text-secondary)] hover:text-[var(--primary-color)] font-medium transition" href="#contact">Contact Us</a>
    </div>
    <a class="hidden md:block bg-[var(--primary-color)] text-white py-2 px-4 rounded-md hover:bg-white hover:text-[var(--primary-color)] border border-[var(--primary-color)] transition font-semibold" href="#admissions">Apply Now</a>
  </nav>
</header>

<main class="flex-1">

<!-- Hero -->
<section class="relative min-h-[60vh] md:min-h-[80vh] flex items-center justify-center text-center bg-cover bg-center" style='background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), url("https://lh3.googleusercontent.com/aida-public/AB6AXuC9Y6x3XGbZgo_nm86Bspfdc-vEBjM8PS2S8sHY6fJb2ke_cj475K7oRfcTx3NSFzt6gAdjjpLQPZkc-UeB-5dYkS9_osWkVcwRMLecmViPxbbd92bFJCI0t8wp924Aiig_afsFHUksYgM0zbfw53a9q2Xl56X6EAJe3wpFyRHToZIlomgvniHDZHqrKxdVJL3eQrG5k6erTxZ-jhAtCAvE5OHHISv55UZmoW97BirlfaTrJUfa5fTKdqJQ_aLKhXUtmajVeejHKzno");'>
  <div class="px-4">
    <h1 class="text-4xl md:text-6xl font-extrabold text-white mb-4 leading-tight">Welcome to GIC Baggha-54</h1>
    <p class="text-lg md:text-xl text-gray-200 max-w-3xl mx-auto">Empowering students for a brighter future through quality education and holistic development.</p>
    <a class="mt-8 inline-block bg-[var(--primary-color)] text-white py-3 px-8 rounded-lg text-lg font-semibold hover:bg-white hover:text-[var(--primary-color)] transition" href="#academics">Explore Our Programs</a>
  </div>
</section>

<!-- About -->
<section class="py-16 sm:py-24 bg-white" id="about">
  <div class="container mx-auto px-6 max-w-7xl">
    <h2 class="text-3xl font-bold mb-6 border-b-2 border-[var(--primary-color)] pb-2 inline-block">About Us</h2>
    <p class="text-base text-[var(--text-secondary)] leading-relaxed mb-4">GIC Baggha-54 is committed to providing a nurturing and stimulating learning environment. Our experienced faculty and state-of-the-art facilities ensure that students receive a well-rounded education that prepares them for future success.</p>
  </div>
</section>

<!-- Academics (merged from first code) -->
<section class="py-16 sm:py-24" id="academics">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-12">
      <h2 class="text-4xl font-extrabold text-[var(--text-primary)] mb-2">Academics</h2>
      <p class="text-lg text-[var(--text-secondary)]">Streams and subjects offered from 9th to 12th grade.</p>
    </div>

    <!-- Grades 9-10 -->
    <div class="mb-16">
      <h3 class="text-3xl font-bold mb-8 text-center">Grades 9-10</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Mathematics -->
        <div class="bg-white shadow-lg rounded-xl border border-gray-200 overflow-hidden hover:-translate-y-2 transition">
          <img class="w-full h-56 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBfArIoD9frhh_XfAL9L4TCSf8esEB1CAcBACQo2C7I5nOLVMDBTgkw4O1iH64rZ37o0sauS-qXEQL5LqKaciUqRbOkfix6QaNUoMwkmqGDYWEa07-lIdW78OVcKnlt6Lc0UOAMsy8vWB63F6UDshIHjNmuQXhI8IAgg3NK0_ezHWch94sGaZYt1H4LINP3WTZDkxDrcH2xIGg6drWXWTNhcgzaJiIIXbjFLabPSRKxIKwsmzUDzykXI8OHybFsbdI20tFmdzd4RK7k"/>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-4">Mathematics Stream</h4>
            <p><b>Hindi:</b> Language, literature, grammar</p>
            <p><b>English:</b> Proficiency, analysis</p>
            <p><b>Science:</b> Physics, Chemistry, Biology basics</p>
            <p><b>Social Science:</b> History, Geography, Civics, Economics</p>
            <p><b>Mathematics:</b> Algebra, Geometry, Trigonometry</p>
          </div>
        </div>
        <!-- Home Science -->
        <div class="bg-white shadow-lg rounded-xl border border-gray-200 overflow-hidden hover:-translate-y-2 transition">
          <img class="w-full h-56 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBpyWeB1uRXiHhV7Mt1k59coV2-OxeMj4kYVy4cl_86BNoVCVRZIh4LMugPyFIL5sHVaef1C_w7ejjmXYFCGHMey3iRUHsuYqQB9hCH43StjhJEN_XLNcaD1n0aUZ5kHEYsk4oUnj8YcLDBRDLg9Q5sImsrXUeLxn-K0HgVWWNwV4JRI81ewKlecsWoOFThSxdkRZ2A7PEWTqLFPdZFRTVttX3xAMf58zluFpC1fOqeudwsycQfi-bb8bDVblL5Xj8JAMD2RuO5-172"/>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-4">Home Science Stream</h4>
            <p><b>Hindi:</b> Language, literature, grammar</p>
            <p><b>English:</b> Proficiency, analysis</p>
            <p><b>Science:</b> Physics, Chemistry, Biology basics</p>
            <p><b>Social Science:</b> History, Geography, Civics, Economics</p>
            <p><b>Home Science:</b> Nutrition, Textiles, Home management</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Grades 11-12 -->
    <div>
      <h3 class="text-3xl font-bold mb-8 text-center">Grades 11-12</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Science -->
        <div class="bg-white shadow-lg rounded-xl border border-gray-200 overflow-hidden hover:-translate-y-2 transition">
          <img class="w-full h-56 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCYAVCV7qjd1-00RyM9hn6sbysskhh1puZpecGBfT5jc3cqsWaoA8oyYDzTRx9qH5H7_KnYapTFYEhiEzUuxgcyzILS5xMYtm6Mh4VhHNHM75QNVbj033mtFTMXkIoDOCwmBb1wqJUF9cRnAve2r5OjUPlgsr_X-6FanALUx2Y5Yol-8B3_RXWNvCyTv6F2jDUO8358BM5FEV5qCk4cV_k6iTp93tnNcXk_HSAEvLIeDBVXFrfKp48aOijgZWrwPBl16ipRt-FG0rcE"/>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-4">Science Stream</h4>
            <p><b>Hindi:</b> Advanced literature, composition</p>
            <p><b>English:</b> Literature, writing skills</p>
            <p><b>Physics:</b> Mechanics, Electricity, Magnetism</p>
            <p><b>Chemistry:</b> Organic, Inorganic, Physical</p>
            <p><b>Mathematics:</b> Algebra, Calculus, Geometry</p>
            <p><b>Biology:</b> Botany, Zoology, Genetics, Ecology</p>
          </div>
        </div>
        <!-- Arts -->
        <div class="bg-white shadow-lg rounded-xl border border-gray-200 overflow-hidden hover:-translate-y-2 transition">
          <img class="w-full h-56 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBsOrexTcCdj5L_PfADlXAbQyiRRmwQKB_pWFzIiThk8n-EReC_SDOsrPNwRaQOo8e2ORV81LgocFkbriNirswdSD4lt5WqqhumLlw9lGeLLVmrMzqJROcYeBdLhDwk2eq8EZ-AF-CsobocPetdeKdFvPez7UEu2jijAr_r7twj0FLtD5DduwshpmxkTy-Y7vw5WHMb-nS1lS4ncE7L6DYCCH3ocXKh3wXD_2mlRPCDiiALMmy14FZjuwIelZqwnM5ueG57oeMJEIXd"/>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-4">Arts Stream</h4>
            <p><b>Hindi:</b> Advanced literature, composition</p>
            <p><b>English:</b> Literature, writing skills</p>
            <p><b>Economics:</b> Micro, Macro principles</p>
            <p><b>Sociology:</b> Society, Culture, Institutions</p>
            <p><b>Political Science:</b> Systems, Theories, IR</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Admissions -->
<section class="py-16 sm:py-24 bg-white" id="admissions">
  <div class="container mx-auto px-6 max-w-7xl">
    <h2 class="text-3xl font-bold mb-6 border-b-2 border-[var(--primary-color)] pb-2 inline-block">Admissions</h2>
    <p class="text-base text-[var(--text-secondary)] leading-relaxed mb-4">We welcome applications from students who are passionate about learning and committed to personal growth. Our admissions process is designed to identify students who will thrive in our challenging and supportive environment.</p>
  </div>
</section>

<!-- Contact -->
<section class="py-16 sm:py-24" id="contact">
  <div class="container mx-auto px-6 max-w-4xl text-center">
    <h2 class="text-3xl font-bold mb-6">Contact Us</h2>
    <p class="text-lg text-[var(--text-secondary)] mb-8">We are here to answer your questions and provide more information about GIC Baggha-54.</p>
    <form class="space-y-6">
      <div class="grid sm:grid-cols-2 gap-6">
        <input class="w-full px-4 py-3 border rounded-md focus:ring-2 focus:ring-[var(--primary-color)]" placeholder="Your Name" type="text"/>
        <input class="w-full px-4 py-3 border rounded-md focus:ring-2 focus:ring-[var(--primary-color)]" placeholder="Your Email" type="email"/>
      </div>
      <textarea class="w-full px-4 py-3 border rounded-md focus:ring-2 focus:ring-[var(--primary-color)]" placeholder="Your Message" rows="5"></textarea>
      <button class="bg-[var(--primary-color)] text-white py-3 px-8 rounded-md hover:bg-white hover:text-[var(--primary-color)] border border-[var(--primary-color)] transition font-semibold text-lg">Send Message</button>
    </form>
  </div>
</section>

</main>

<!-- Footer -->
<footer class="bg-[var(--text-primary)] text-white py-8">
  <div class="container mx-auto px-6 text-center max-w-7xl">
    <p class="text-gray-400">© 2023 GIC Baggha
