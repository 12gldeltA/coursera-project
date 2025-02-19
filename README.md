<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
    <title>Document</title>
</head>
<body>
    <header class="text-gray-600 body-font shadow-md">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
            <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-blue-500 rounded-full" viewBox="0 0 24 24">
                    <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
                </svg>
                <span class="ml-3 text-xl font-bold text-gray-900">Elite Fitness</span>
            </a>
            <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400 flex flex-wrap items-center text-base justify-center space-x-6">
                <a href="#" class="hover:text-gray-900 font-medium">Home</a>
                <a href="#about" class="hover:text-gray-900 font-medium">About</a>
                <a href="#services" class="hover:text-gray-900 font-medium">Services</a>
                <a href="#contact" class="hover:text-gray-900 font-medium">Contact</a>
            </nav>
            <a href="#join" class="inline-flex items-center bg-blue-500 text-white border-0 py-2 px-4 focus:outline-none hover:bg-blue-600 rounded-lg text-base mt-4 md:mt-0 transition">
                Join Now
                <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7"></path>
                </svg>
            </a>
        </div>
    </header>
    
    <section class="text-gray-600 body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
            <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
                <h1 class="title-font sm:text-5xl text-4xl mb-4 font-bold text-gray-900">
                    Transform Your Body, <br class="hidden lg:inline-block">Elevate Your Fitness
                </h1>
                <p class="mb-8 leading-relaxed text-lg text-gray-700">
                    Achieve your fitness goals with expert training, modern equipment, and a supportive community. Join us today and take your workouts to the next level!
                </p>
                <div class="flex justify-center">
                    <a href="#join" class="inline-flex text-white bg-blue-500 border-0 py-3 px-6 focus:outline-none hover:bg-blue-600 rounded-lg text-lg font-semibold">
                        Get Started
                    </a>
                    <a href="#about" class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-3 px-6 focus:outline-none hover:bg-gray-200 rounded-lg text-lg font-semibold">
                        Learn More
                    </a>
                </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
                <img class="object-cover object-center rounded-lg shadow-lg" 
                alt="Gym Workout" 
                src="https://images.unsplash.com/photo-1526506118085-60ce8714f8c5?q=80&w=2487&auto=format&fit=crop">
           
            </div>
        </div>
    </section>
    

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pricing Page</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-color: #f4f4f4;
                text-align: center;
            }
            .pricing-container {
                display: flex;
                justify-content: center;
                align-items: center;
                flex-wrap: wrap;
                padding: 50px 20px;
            }
            .pricing-card {
                background: white;
                border-radius: 10px;
                padding: 20px;
                margin: 15px;
                width: 300px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                transition: transform 0.3s ease-in-out;
            }
            .pricing-card:hover {
                transform: scale(1.05);
            }
            .pricing-title {
                font-size: 24px;
                font-weight: bold;
                margin-bottom: 10px;
            }
            .price {
                font-size: 30px;
                color: #27ae60;
                font-weight: bold;
                margin-bottom: 10px;
            }
            .features {
                list-style: none;
                padding: 0;
                margin-bottom: 20px;
            }
            .features li {
                margin: 10px 0;
                font-size: 16px;
            }
            .btn {
                display: inline-block;
                padding: 10px 20px;
                background: #27ae60;
                color: white;
                text-decoration: none;
                border-radius: 5px;
                font-weight: bold;
                transition: background 0.3s;
            }
            .btn:hover {
                background: #219150;
            }
        </style>
    </head>
    <body>
        <h1>Our Pricing Plans</h1>
        <div class="pricing-container">
            <div class="pricing-card">
                <div class="pricing-title">Basic Plan</div>
                <div class="price">$9.99/month</div>
                <ul class="features">
                    <li>✔ 10GB Storage</li>
                    <li>✔ Basic Support</li>
                    <li>✔ Single User</li>
                </ul>
                <a href="#" class="btn">Choose Plan</a>
            </div>
            <div class="pricing-card">
                <div class="pricing-title">Standard Plan</div>
                <div class="price">$19.99/month</div>
                <ul class="features">
                    <li>✔ 50GB Storage</li>
                    <li>✔ Priority Support</li>
                    <li>✔ Up to 5 Users</li>
                </ul>
                <a href="#" class="btn">Choose Plan</a>
            </div>
            <div class="pricing-card">
                <div class="pricing-title">Premium Plan</div>
                <div class="price">$29.99/month</div>
                <ul class="features">
                    <li>✔ 200GB Storage</li>
                    <li>✔ 24/7 Support</li>
                    <li>✔ Unlimited Users</li>
                </ul>
                <a href="#" class="btn">Choose Plan</a>
            </div>
        </div>
    </body>
    </html>

    <section class="bg-gray-100 py-16">
        <div class="container mx-auto px-6">
          <div class="flex flex-wrap -m-4 text-center">
            <div class="p-6 md:w-1/4 sm:w-1/2 w-full">
              <h2 class="text-4xl font-semibold text-gray-900">2.7K</h2>
              <p class="mt-2 text-lg text-gray-600">Active Users</p>
            </div>
            <div class="p-6 md:w-1/4 sm:w-1/2 w-full">
              <h2 class="text-4xl font-semibold text-gray-900">1.8K</h2>
              <p class="mt-2 text-lg text-gray-600">Subscribers</p>
            </div>
            <div class="p-6 md:w-1/4 sm:w-1/2 w-full">
              <h2 class="text-4xl font-semibold text-gray-900">35</h2>
              <p class="mt-2 text-lg text-gray-600">Downloads</p>
            </div>
            <div class="p-6 md:w-1/4 sm:w-1/2 w-full">
              <h2 class="text-4xl font-semibold text-gray-900">4</h2>
              <p class="mt-2 text-lg text-gray-600">Products</p>
            </div>
          </div>
        </div>
      </section>
      
      <section class="bg-gray-100 py-16">
        <div class="container mx-auto px-6">
          <div class="flex flex-wrap -m-4 text-center">
            <div class="flex relative pt-10 pb-20 sm:items-center md:w-2/3 mx-auto">
              <div class="h-full w-6 absolute inset-0 flex items-center justify-center">
                <div class="h-full w-1 bg-gray-300 pointer-events-none"></div>
              </div>
              <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 text-white inline-flex items-center justify-center font-bold text-sm">1</div>
              <div class="flex-grow md:pl-8 pl-6 flex sm:items-center items-start flex-col sm:flex-row">
                <div class="flex-shrink-0 w-24 h-24 bg-red-100 text-red-500 rounded-full inline-flex items-center justify-center">
                  <svg class="w-12 h-12" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24">
                    <path d="M12 2L4 14h16L12 2z"></path>
                  </svg>
                </div>
                <div class="flex-grow sm:pl-6 mt-6 sm:mt-0">
                  <h2 class="font-bold text-gray-900 mb-1 text-xl">Join Our Gym</h2>
                  <p class="leading-relaxed text-gray-600">Start your fitness journey with a personalized training plan and state-of-the-art equipment.</p>
                </div>
              </div>
            </div>
      
            <div class="flex relative pb-20 sm:items-center md:w-2/3 mx-auto">
              <div class="h-full w-6 absolute inset-0 flex items-center justify-center">
                <div class="h-full w-1 bg-gray-300 pointer-events-none"></div>
              </div>
              <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 text-white inline-flex items-center justify-center font-bold text-sm">2</div>
              <div class="flex-grow md:pl-8 pl-6 flex sm:items-center items-start flex-col sm:flex-row">
                <div class="flex-shrink-0 w-24 h-24 bg-red-100 text-red-500 rounded-full inline-flex items-center justify-center">
                  <svg class="w-12 h-12" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5v14"></path>
                  </svg>
                </div>
                <div class="flex-grow sm:pl-6 mt-6 sm:mt-0">
                  <h2 class="font-bold text-gray-900 mb-1 text-xl">Work with Trainers</h2>
                  <p class="leading-relaxed text-gray-600">Our expert trainers guide you with customized workout routines for maximum results.</p>
                </div>
              </div>
            </div>
      
            <div class="flex relative pb-20 sm:items-center md:w-2/3 mx-auto">
              <div class="h-full w-6 absolute inset-0 flex items-center justify-center">
                <div class="h-full w-1 bg-gray-300 pointer-events-none"></div>
              </div>
              <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 text-white inline-flex items-center justify-center font-bold text-sm">3</div>
              <div class="flex-grow md:pl-8 pl-6 flex sm:items-center items-start flex-col sm:flex-row">
                <div class="flex-shrink-0 w-24 h-24 bg-red-100 text-red-500 rounded-full inline-flex items-center justify-center">
                  <svg class="w-12 h-12" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24">
                    <path d="M12 6v6l4 2"></path>
                  </svg>
                </div>
                <div class="flex-grow sm:pl-6 mt-6 sm:mt-0">
                  <h2 class="font-bold text-gray-900 mb-1 text-xl">Track Your Progress</h2>
                  <p class="leading-relaxed text-gray-600">Monitor your fitness goals with our progress tracking tools and assessments.</p>
                </div>
              </div>
            </div>
      
            <div class="flex relative pb-10 sm:items-center md:w-2/3 mx-auto">
              <div class="h-full w-6 absolute inset-0 flex items-center justify-center">
                <div class="h-full w-1 bg-gray-300 pointer-events-none"></div>
              </div>
              <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 text-white inline-flex items-center justify-center font-bold text-sm">4</div>
              <div class="flex-grow md:pl-8 pl-6 flex sm:items-center items-start flex-col sm:flex-row">
                <div class="flex-shrink-0 w-24 h-24 bg-red-100 text-red-500 rounded-full inline-flex items-center justify-center">
                  <svg class="w-12 h-12" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24">
                    <path d="M4 20h16M4 16h16M4 12h16"></path>
                  </svg>
                </div>
                <div class="flex-grow sm:pl-6 mt-6 sm:mt-0">
                  <h2 class="font-bold text-gray-900 mb-1 text-xl">Achieve Your Goals</h2>
                  <p class="leading-relaxed text-gray-600">Push your limits and reach your peak fitness with our dynamic workout programs.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="text-gray-600 body-font">
        <div class="container px-5 py-24 mx-auto">
          <h1 class="text-4xl font-bold text-center text-gray-900 mb-12">Member Testimonials</h1>
          <div class="flex flex-wrap -m-4">
            <div class="p-4 md:w-1/2 w-full">
              <div class="h-full bg-white shadow-lg p-8 rounded-lg">
                <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-6 h-6 text-red-500 mb-4" viewBox="0 0 975.036 975.036">
                  <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50z"></path>
                </svg>
                <p class="leading-relaxed mb-6 text-gray-700">"This gym has completely transformed my fitness journey! The trainers are amazing, and the atmosphere is highly motivating."</p>
                <div class="flex items-center">
                  <img alt="testimonial" src="https://dummyimage.com/106x106" class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center">
                  <div class="flex-grow flex flex-col pl-4">
                    <span class="font-bold text-gray-900">John Doe</span>
                    <span class="text-red-500 text-sm">Fitness Enthusiast</span>
                  </div>
                </div>
              </div>
            </div>
            <div class="p-4 md:w-1/2 w-full">
              <div class="h-full bg-white shadow-lg p-8 rounded-lg">
                <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-6 h-6 text-red-500 mb-4" viewBox="0 0 975.036 975.036">
                  <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50z"></path>
                </svg>
                <p class="leading-relaxed mb-6 text-gray-700">"The personalized workout plans and friendly community make this gym stand out. I’ve seen incredible results!"</p>
                <div class="flex items-center">
                  <img alt="testimonial" src="https://dummyimage.com/107x107" class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center">
                  <div class="flex-grow flex flex-col pl-4">
                    <span class="font-bold text-gray-900">Jane Smith</span>
                    <span class="text-red-500 text-sm">Certified Trainer</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
