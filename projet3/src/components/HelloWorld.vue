<template>
    
        <nav class="p-16 flex justify-between gap-32">
                
                <div class="flex ">
                    <img class=""  src="assete/000logo.png" alt="logo">
                    
                </div>
            
        
                <div class="flex hidden lg:flex">
                    <ul class="font-bold text-2xl flex gap-8 text-gray-600 items-center">
                    
                        <li class="hover:text-indigo-500"><a href="#">Home</a></li>
                    
                        <li class="hover:text-indigo-500"><a href="#">About ME</a></li>
        
                        <li class="hover:text-indigo-500"><a href="#">Services</a></li>
        
                        <li class="hover:text-indigo-500"><a href="#">Blog</a></li>
        
                        <li class="mr-32 hover:text-indigo-500"><a href="#">Contact Me</a></li>
        
                    </ul>
        
                    <div class="">
                        <button class="text-white text-2xl rounded-full py-2 px-8 hidden lg:flex transition ease-in-out delay-150 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 ...">Let's chat</button>
                    </div>
                </div>

                <button class="sm:block md:block lg:hidden"><img class="w-10 h-10" src="assete/hamburger-menu-icon.png"></button>
        </nav>



</template>

<script>


export default {
  name: 'HelloWorld',
  
  components: {
    
  }
 
}
</script>

<style>

</style>
