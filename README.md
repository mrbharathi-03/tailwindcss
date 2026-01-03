<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>yellow</title>

<!--cdn link-->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">

</head>
<body>
    
<!--nav bar-->

<div class="bg-green-100 flex p-3 justify-between items-center shadow-md sticky top-0 z-10">

    <h1 class="text-2xl">Green</h1>

 <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="md:hidden w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
</svg>



    <ul class="flex gap-5 text-grey-500 hidden md:flex">

        <li class="hover:underline hover:text-black"><a href="./intex.html">Home</a></li>

        <li class="hover:underline hover:text-black"><a href="./product.html">Product</a></li>

        <li class="hover:underline hover:text-black"><a href="contact.html">Contact</a></li>
    </ul>

</div>

<!--header section -->

<section class="bg-green-200  p-4 flex justify-center ">

    <div>
   <p class="text-lg">This is a simple webpage with a green theme </p>
 <h1 class="text-4xl font-bold mb-2">Welcome to Green Page</h1>
    <div>
        <button class="bg-black text-white p-2 rounded mt-2 ">Get Started</button>
        <button class="rounded border border-black p-2">watch video </button>
    </div>

    <p class="mt-3">160+ plants | 100+ clients </p>

    </div>

  <div class="hidden md:block p-5">

    <img src="images.jpg" alt="header images">
  </div>

</section>

<!--About section-->

<section>
    <!--title-->
    <div>
        <h2 class="text-3xl font-bold text-center mt-5">About Green</h2>
        <p class="text-center mt-2">Green is a color that symbolizes nature</p>
    </div>
    <!--boxes-->

    <div class=" md:flex" >

        <div class="border border-black  p-5 m-6 text-center " >

           <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-20 inline">
  <path stroke-linecap="round" stroke-linejoin="round" d="m16.862 4.487 1.687-1.688a1.875 1.875 0 1 1 2.652 2.652L10.582 16.07a4.5 4.5 0 0 1-1.897 1.13L6 18l.8-2.685a4.5 4.5 0 0 1 1.13-1.897l8.932-8.931Zm0 0L19.5 7.125M18 14v4.75A2.25 2.25 0 0 1 15.75 21H5.25A2.25 2.25 0 0 1 3 18.75V8.25A2.25 2.25 0 0 1 5.25 6H10" />
</svg>

            <h6 class="font-medium text-center mt-2 " >Large Assortment</h6>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error soluta iure omnis quod, voluptate, rerum est, illo cumque earum iste aperiam id eos culpa temporibus praesentium accusamus excepturi numquam perferendis.</p>
        </div>

        <div class="border border-black  p-5 m-6 text-center ">

<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-20 inline">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 10.5V6a3.75 3.75 0 1 0-7.5 0v4.5m11.356-1.993 1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 0 1-1.12-1.243l1.264-12A1.125 1.125 0 0 1 5.513 7.5h12.974c.576 0 1.059.435 1.119 1.007ZM8.625 10.5a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm7.5 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z" />
</svg>

            <h6 class="font-medium text-center mt-2">Free Shipping</h6>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse eius facilis soluta delectus omnis praesentium ad tempora vitae? Odit cum commodi obcaecati in corporis impedit totam quos accusamus necessitatibus natus!</p>
                </div>

        <div class="border border-black  p-5 m-6 text-center ">

        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-20 inline">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>

            <h6 class="font-medium text-center mt-2">24/7 Support</h6>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et obcaecati facilis ad sint, eum, tenetur amet veniam minima esse autem neque perspiciatis saepe ipsa facere! Consectetur fugiat cumque ut expedita.</p>
        </div>

    </div>

</section>

<!--seller section-->

<section class="p-4 text-center">
  
   <h1 class="font-bold text-3xl text-center p-4">Best Seller</h1>
  

  <div class="grid grid-cols-2 md:grid-cols-4 gap-2 p-5">

    <div>
      <img src="New folder/seller 1.jpg" class="inline hover:shadow-xl transform hover:-translate-y-2" alt="">
      <h1>Rose plant</h1>
      <p>Price: $65</p>
    </div>

    <div>
      <img src="New folder/seller 5.jpg" class="inline hover:shadow-xl transform hover:-translate-y-2" alt="">
      <h1>Pink Rose</h1>
      <p>Price: $55</p>
    </div>

    <div>
      <img src="New folder/seller 3.jpg" class="inline hover:shadow-xl transform hover:-translate-y-2" alt="">
      <h1>Red Rose</h1>
      <p>Price: $35</p>
    </div>

    <div>
      <img src="New folder/seller 4.jpg" class="inline hover:shadow-xl transform hover:-translate-y-2" alt="">
      <h1>White Lilly</h1>
      <p>Price: $50</p>
    </div>

  </div>
</section>
 
<!--customer review section-->
<section>
   <h1 class="text-3xl text-center m-5 font-bold">Customer Reviews</h1>

   <div class="flex flex-col gap-5 justify-center m-5">
  
    <div class="bg-green-900 p-5 container text-white">
<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam architecto repellendus placeat harum voluptas quibusdam nulla dolores accusantium, sit itaque quia rerum distinctio necessitatibus nostrum nam, omnis ducimus expedita adipisci.</p>
<p class="font-bold text-yellow-300">Ms</p>   
</div>

 <div class="bg-green-900 p-5 container text-white">
<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam architecto repellendus placeat harum voluptas quibusdam nulla dolores accusantium, sit itaque quia rerum distinctio necessitatibus nostrum nam, omnis ducimus expedita adipisci.</p>
<p class="font-bold text-yellow-300">Kl</p>  
</div>

 <div class="bg-green-900 p-5 container text-white">
<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam architecto repellendus placeat harum voluptas quibusdam nulla dolores accusantium, sit itaque quia rerum distinctio necessitatibus nostrum nam, omnis ducimus expedita adipisci.</p>
<p class="font-bold text-yellow-300">Vk</p>  
</div>

   </div>
</section> 

<!--News later section-->

<section class=" p-5 text-center">
   <h1 class="text-3xl text-center font-bold m-5">Join Our Newsletter</h1>
   <p class="m-5">minima alias ut exercitationem esse tenetur neque tempora harum</p>
<input type="text" class=" border border-black p-2 m-2" style="width:80%;"> <br>
<button class="bg-black text-white p-2 rounded m-2 underline ">Subscribe</button>
</section>

<!--footer section-->
<section class="p-5 bg-green-100 flex flex-col gap-5"> 

<h1 class="text-4xl font-bold  ">Green</h1>
<p> blanditiis mollitia repellendus in? Doloremque ipsum aliquid quia reiciendis</p>
<p>@ 2019 green.com</p>
</section>
</body>
</html>  
