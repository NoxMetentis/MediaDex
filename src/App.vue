



<template>
   

 <div>
<div class="flex justify-center" v-if="showModal">
      <Modal theme="sales" @close="toggleModal">
        <template v-slot:links>
          <a class="bg-blue-400 rounded-xl p-3 text-white" href="#">Sign Up </a>
           <a class="bg-blue-400 rounded-xl p-3 text-white" href="#"> More Shit</a>
        </template>
        <h1>Hello</h1>
        <p>Yea i just did that </p>
      </Modal>
    </div>
    <div class="flex justify-center" v-if="showModalTwo">
      <Modal @close="toggleModalTwo">
        <h1>Sheeesh</h1>
        <p>I might have a slight idea </p>
      </Modal>
    </div>
  
    <div class="flex justify-center mt-20">
       <button class="rounded-xl bg-gray-200 px-8 py-3 shadow-md hover:bg-gray-300 text-lg font-semibold" @click="toggleModal">Open Model1</button>
      <button class="rounded-xl bg-gray-500 px-8 py-3 shadow-md hover:bg-gray-300 text-lg font-semibold ml-4" @click="toggleModalTwo">Open Model2</button>

    </div>
 </div>
  <section class="px-4 py-4">
        <nav class="flex justify-between items-center"><!--nav starts here-->
            <div class="text-3xl font-semibold text-blue-500 hover:text-blue-600">
               <a href="#" class="flex items-center">
                              <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 20 20" fill="currentColor">
  <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
</svg> 
                MyRater
              </a>
            </div>
            <div class="font-sans flex" >
                <div class="transform hover:scale-105"><a href="#" class="text-xs font-bold font bg-blue-500 rounded-full text-white px-4 py-3 hover:shadow-md shadow-sm hover:bg-blue-600 transition hover:duration-500"> Home</a></div>
                <div class="transform hover:scale-105"><a href="#" class="text-xs font-semibold font bg-blue-500 rounded-full ml-2 text-white px-5 py-3 uppercase hover:shadow-md shadow-sm hover:bg-blue-600 transition hover:duration-500"> Login/SignUp (NA)</a></div>
                
            </div>
             </nav><!--nav ends here-->

             <header class="mt-10 max-w-4xl mx-auto text-center"> 
                 <div class="max-w-2xl mx-auto ">
                    
                        <h1 class="text-5xl font-OpenSans">
                            Latest <span class="text-blue-500 "> Updates On All The Mangas, Novels And</span> Light Novels
                        </h1>
                        <h2 class="text-lg font-semibold italic mt-3">
                            By Avas <img class=" inline-flex" src="./images/user.svg" alt="User">
                        </h2>
                        <p class="mt-5">
                            This website shall be used to update the status of all the Manga, Light Novels and Anime I have read. It will contain my review of the media and a short synopsis.
                        </p>

                        <div class="flex justify-center mt-8 space-x-4">
                            <!--category-->
                          <span class="bg-gray-200 rounded-xl inline-block items-center relative hover:cursor-pointer hover:shadow-md hover:bg-gray-300"> 
                            <select class="pl-3 pr-9 py-2 appearance-none bg-transparent text-sm font-semibold">
                                <option value="Category" selected disabled>Category(WIP)</option>
                                <option value="Category">Manga</option>
                                <option value="Category">Light Novel</option>
                                <option value="Category">Anime</option>
                            </select>
                            <svg class="absolute pointer-events-none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" fill="currentColor"  width="22" height="22" style="right: 12px; top: 10px;">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                              </svg>
                          </span>
                          

                          <!--other-->
                          <span class="bg-gray-200 rounded-xl inline-block items-center relative hover:cursor-pointer hover:shadow-md hover:bg-gray-300"> 
                            <select class="pl-3 pr-9 py-2 appearance-none bg-transparent text-sm font-semibold">
                                <option value="Category" selected disabled>Other Filters(WIP)</option>
                                <option value="Category">Reading</option>
                                <option value="Category">Completed</option>
                                <option value="Category">Dropped </option>
                            </select>
                            <svg class="absolute pointer-events-none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" fill="currentColor"  width="22" height="22" style="right: 12px; top: 10px;">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                              </svg>
                          </span>
                          <!--search-->
                          <span class="relative inline-flex items-center bg-gray-100 rounded-xl px-3 py-2 hover:shadow-md hover:cursor-pointer hover:bg-gray-200">
                            <form action="#" method="get">
                                <input type="text" name="search" placeholder="Seach Here...(NA)" class="bg-transparent placeholder-black font-semibold text-sm">
                            </form>
                        </span>
                        </div>
                </div>
        </header>
         <main class="max-w-5xl mx-auto mt-20">
               <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--article 1-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/Overlord.png" alt="robots" class="rounded-xl w-full" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           Overlord
                                            <span class="mt-5 mb-2 block text-gray-400 text-xs">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1">
                                        <p>
                                            The final hour of the popular virtual reality game Yggdrasil has come. However, Momonga, a powerful wizard and master of the dark guild Ainz Ooal Gown, decides to spend his last few moments in the game as the servers begin to shut down. To his surprise, despite the clock having struck midnight, Momonga is still fully conscious as his character and, moreover, the non-player characters appear to have developed personalities of their own!
                                        </p>
                                        <p class="mt-3">
                                          Confronted with this abnormal situation, Momonga commands his loyal servants to help him investigate and take control of this new world, with the hopes of figuring out what has caused this development and if there may be others in the same predicament.(Synopsis from MAL)
                                        </p>
                                </div>
                                <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/KuganeMaruyama.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Maruyama Kugane</h1>
                                            <h2> Author of Overlord</h2>
                                        </div>
                                        
                                    </div>
                                    <div>
                                        <button @click="toggleModal" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
         </main>
             </section>
    
   

</template>


<script>
import Modal from  './components/Modal.vue'
import VScrollLock from 'v-scroll-lock'



export default{
  name:'app',
  components:{Modal},
  data(){
    return {
      showModal: false,
      showModalTwo: false,
    }
  },
  methods: {
   toggleModalTwo(){
      this.showModalTwo=!this.showModalTwo
    },
    toggleModal(){
      this.showModal=!this.showModal
    } 
  }
 
}
 
</script>

