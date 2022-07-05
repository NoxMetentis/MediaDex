



<template>
 <div>
    <div class="flex justify-center" v-if="showM1">
      <Modal @close="toggleM1">  
       <article><!--modelm1-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1">
                             <div>
                                <img src="./images/Overlord.png" alt="Overlord" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/KuganeMaruyama.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Maruyama Kugane</h1>
                                            <h2> Author of Overlord</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           Overlord
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                           The manga starts off in the same manner as the Anime however, it still fails to evoke the same emotions that were conjured up in the anime. The artsyle is engaing and the story is conveyed coherently but, the updates are infrequent and inconsistent.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  3.5/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Action, Adventure, Comedy, Drama, Fantasy, Isekai, Sci-Fi


                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Video Game, Demons, Monsters
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
    </div>
      <div class="flex justify-center" v-if="showM2">
      <Modal @close="toggleM2">
       <article><!--modelm2-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1">
                             <div>
                                <img src="./images/IrumaManga.jpg" alt="Iruma" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/OsamuNishi.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Osamu Nishi</h1>
                                            <h2> Author of Mairimashita! Iruma kun</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                          Mairimashita! Iruma kun
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                           The manga chronicles the school life of a human boy in the underworld, where he has to disguise himself
                                           among them. It is a pretty good slice of life manga with a fair amount of action and drama as well. The artstyle is very pretty and the storytelling is quite emotional as well. The characters are written well and are developed even better as the manga continues. Overall a very good manga in its genre.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  4.5/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Action, School Life, Comedy, Romance, Fantasy, Isekai


                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Magic, Demons, Monsters
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
      </div>
      <div class="flex justify-center" v-if="showM3">
      <Modal @close="toggleM3">
       <article><!--modelm3-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1">
                             <div>
                                <img src="./images/VoynichHotel.jpg" alt="Hotel" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/Dowman.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Dowman Sayman</h1>
                                            <h2> Author of The Voynich Hotel</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Completed</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                       The Voynich Hotel
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                           The manga has a pretty grim and macabre artsyle. It focuses on a hotel run by witches and features a lot of dark comedy and violence. It has a pretty sweet romance plot as the story develops. The storyline is well written and the ending is done well. An overall pretty good manga.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  4.0/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Horror, Mystery, Comedy, Horror, Romance, Slice of Life

                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Supernatural, Seinen
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
      </div>
      <div class="flex justify-center" v-if="showM4">
      <Modal @close="toggleM4">
       <article><!--modelm4-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1">
                             <div>
                                <img src="./images/OPMManga.jpg" alt="OPM" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/One.jpg" alt="One">
                                        <div class="ml-2">
                                            <h1 class="font-bold">One</h1>
                                            <h2> Author of One Punch Man</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           One Punch Man
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                           One Punch Man is an action packed manga with an abundance of fight scenes and thirlling combat. It is able to portray a lot in its pages thanks to Murata Yuusuke who is the artist responsible for the work. The artstyle greatly complements the story which chronicles the journey of a part time hero Saitama. A masterpiece in its own right.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  4.6/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Action, Superhero, Comedy, Drama, Mystery, Thirller, Sci-Fi


                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Martial Arts, Animals, Monsters
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
      </div>
      <div class="flex justify-center" v-if="showM5">
      <Modal @close="toggleM5">
       <article><!--modelm5-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1">
                             <div>
                                <img src="./images/Spy.jpg" alt="Spy" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/Endo.png" alt="Endo">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Endou Tatsuya</h1>
                                            <h2> Author of SPY×FAMILY</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           SPY×FAMILY
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                           The hit manga showcasing the make shift family consisting of Loid Forger who is secretly a spy, Anya Forger who is secretly an esper and Yor who is secretly an assasin who try to hide their secret identities and eventually form a real family is very hartwarming. There are many thrilling moments filled with action and many emotional scenes as well. The artstyle is wonderfull and the sttory is on a league of its own. A must read manga.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  4.8/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Action, Adventure, Comedy, Slice of Life


                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Martial Arts, Supernatural, School life
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
            
 </div>
  <div class="flex justify-center" v-if="showA1">
 <Modal @close="toggleA1">
       <article><!--modela1-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1 border-2 border-red-200">
                             <div>
                                <img src="./images/OverlordAnime.jpg" alt="robots" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/KuganeMaruyama.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Maruyama Kugane</h1>
                                            <h2> Author of Overlord</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Anime</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           Overlord
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                        The anime is one of the pioneers in the Isekai genre and is action-packed with epic fights and violence. It also has a reasonable amount of world-building and narrative progression.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  3.8/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Comedy, Fantasy, Supernatural
                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Video Game, Isekai
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
  </div>
  <div class="flex justify-center" v-if="showN1">
 <Modal @close="toggleN1">
       <article><!--modeln1-->
                         <div class="py-6 px-5 grid grid-cols-3">
                            <div class="mr-8 col-span-1 border-2 border-red-200">
                             <div>
                                <img src="./images/OverlordNovel.jpg" alt="robots" class="rounded-xl w-full overflow-auto">
                             </div>           
                                 <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/KuganeMaruyama.jpg" alt="Maruyama">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Maruyama Kugane</h1>
                                            <h2> Author of Overlord</h2>
                                        </div>
                                        
                                    </div>
                                
                                </footer>
                            </div>
                            <div class="col-span-2 justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Novel</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                           Overlord
                                            <span class="mt-2 mb-2 block text-gray-400 text-xs border-b-2 border-gray-400">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1 text-justify ml-2">
                                        <h1 class="text-lg font-semibold"> Review</h1>
                                        <p>
                                          The novel is the precursor to all the other Manga and the Anime. It is a thoroughly well-written isekai light novel with many shifts in perspectives. It does not follow the cliche isekai formula and focuses on world builind and developing characters.
                                        </p>
                                  
                                         <p class="mt-3">
                                         <span class=" font-semibold text-md ">Rating:  </span>  4.3/5
                                        </p>  
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Genres: </span> Action, Fantasy, Supernatural, Mature
                                        </p>
                                        <p class="mt-3">
                                          <span class=" font-semibold text-md "> Themes: </span> Video Game, Isekai, Antihero Protagonist
                                        </p>
                                </div>
                            </div>
                         </div>
               </article> 
      </Modal>
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

             <header class="mt-10 max-w-4xl mx-auto text-center z-10"> 
                 <div class="max-w-2xl mx-auto ">
                    
                        <h1 class="text-5xl font-OpenSans">
                            Latest <span class="text-blue-500 "> Updates On All The Mangas, Anime And</span> Light Novels
                        </h1>
                        <h2 class="text-lg font-semibold italic mt-3">
                            By Avas <img class=" inline-flex" src="./images/user.svg" alt="User">
                        </h2>
                        <p class="mt-5">
                            This website shall be used to update the status of all the Manga, Light Novels and Anime I have read. It will contain my review of the media and a short synopsis.
                        </p>
                        <div class="mt-4 border-t-2 flex justify-between"> 
                           <p class=" pl-40 "> Select Category </p>
                            <p class=" pr-52 "> Search Bar: </p>
                        </div>
                       
                        <div class="flex justify-center mt-2 space-x-4">
                            <!--category-->
                          <span class="bg-gray-200 rounded-xl inline-block items-center relative hover:cursor-pointer hover:shadow-md hover:bg-gray-300"> 
                            
                            <select class="pl-3 pr-9 py-2 appearance-none bg-transparent text-sm font-semibold" v-model="selected" @click="checkType"> 
                              placeholder
                             <option disabled value>Please select one</option>
                                <option value="Manga">Manga</option>
                                <option value="LN">Light Novel</option>
                                <option value="Anime">Anime</option>
                            </select>
                           <label for=""></label>       
                            <svg class="absolute pointer-events-none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" fill="currentColor"  width="22" height="22" style="right: 12px; top: 10px;">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                              </svg>
                          </span>
                          <!--search-->
                          <span class="relative inline-flex items-center bg-gray-100 rounded-xl px-3 py-2 hover:shadow-md hover:cursor-pointer hover:bg-gray-200">
                            <form action="#" method="get">
                                <input type="text" name="search" placeholder="Seach Here...(WIP)" class="bg-transparent placeholder-black font-semibold text-sm">
                            </form>
                        </span>
                        </div>
                </div>
        </header>
         <main class="max-w-5xl mx-auto mt-20">
          <div v-if="isNovel">
              <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--article 1-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/OverlordNovel.jpg" alt="robots" class="rounded-xl w-full" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Novel</a>
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
                                       In 21st century, world entered a new stage of VR games…and “YGGDRASIL” is considered top of all MMORPG…but, After announcing that all its servers will be off, the internet game ‘Yggdrasil’ shut down…or so was supposed to happen, but for some reason, the player character did not log out some time after the server was closed. 
                                        </p>
                                        <p class="mt-3">
                                          NPCs start to become sentient. A normal youth who loves gaming in the real world seemed to have been transported into an alternate world along with his guild, becoming the strongest mage with the appearance of a skeleton, Momonga. He leads his guild “Ainz Ooal Gown” towards an unprecedented legendary fantasy adventure!
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
                                        <button @click="toggleN1" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
            </div>
              
                <div v-if="isAnime">
          <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--article 2-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/OverlordAnime.jpg" alt="robots" class="rounded-xl w-full" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Anime</a>
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
                                          Momonga is an average salaryman who spends his free time playing Yggdrasil, a DMMO-RPG (Dive Massively Multiplayer Online Role-Playing Game) well-known across Japan for its immense world and limitless customization. Unfortunately, all good things come to an end, and Yggdrasil's servers shut down in the year 2138. Wanting to witness the game’s final hours, Momonga, the leader of the guild Ainz Ooal Gown, logs in for the last time and heads toward the guild’s headquarters.
                                        </p>
                                        <p class="mt-3">
                                          After reminiscing about his comrades and adventures, Momonga prepares for the server to automatically log him out as the clock strikes midnight. However, he is not forcefully booted out of the game. Instead, he finds himself in a new world—now trapped in the body of his avatar and where non-player characters are aware of their feelings.
                                        </p>
                                        <p class="mt-3"> 
                                          Left with no other options, Momonga takes on the name of his guild in hopes that other players would recognize Ainz Ooal Gown. Determined to make sense of the bizarre situation, Momonga embarks on a journey to unravel the mysteries hidden in this uncharted world. <br>
                                          [Written by MAL Rewrite]
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
                                        <button @click="toggleA1" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                </div>
                  <div v-if="isManga">
                <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--Manga1-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/Overlord.png" alt="Overlord" class="rounded-xl w-full object-cover" style="height:500px;">
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
                                          Confronted with this abnormal situation, Momonga commands his loyal servants to help him investigate and take control of this new world, with the hopes of figuring out what has caused this development and if there may be others in the same predicament.(Synopsis from Mangadex)
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
                                        <button @click="toggleM1" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--Manga2-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/IrumaManga.jpg" alt="Iruma" class="rounded-xl w-full object-cover" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                          Mairimashita! Iruma-kun
                                            <span class="mt-5 mb-2 block text-gray-400 text-xs">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1">
                                        <p>
                                            Fourteen-year-old Suzuki Iruma had just been abandoned and sold to a demon by his irresponsible parents! However, much to his surprise, he finds himself now living with the demon as his adopted grandson. He's then enrolled into a school where his doting "demon" grandfather, Sullivan, works as the principal. Thus begins the cowardly Iruma-kun's extraordinary school life among the otherworldly, meeting many colorful faces, taking on daunting challenges, and facing his true self as he rises to become someone great.
                                        </p>
                                        <p class="mt-3">
                                         Cozy magical slice of life with occasional urban terrorism.(Synopsis from Mangadex)
                                        </p>
                                </div>
                                <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/OsamuNishi.jpg" alt="Osamu">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Osamu Nishi</h1>
                                            <h2> Author of Mairimashita! Iruma Kun</h2>
                                        </div>
                                        
                                    </div>
                                    <div>
                                        <button @click="toggleM2" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--Manga3-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/VoynichHotel.jpg" alt="Hotel" class="rounded-xl w-full object-cover" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Completed</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                         The Voynich Hotel
                                            <span class="mt-5 mb-2 block text-gray-400 text-xs">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1">
                                        <p>
                                            Staffed by murderous maids and situated on a war-ravaged island, the Voynich Hotel is far from your run-of-the-mill vacation destination–but it’s not such a bad place to lie low for ex-yakuza Kazuki Taizou, who’s on the run from his so-called family. As he settles into his weird new life, this darkly comedic manga winds through plots both nefarious and romantic, delving ever deeper into the island’s witchy–and sometimes demonic–strangeness.
                                        </p>
                                        <p class="mt-3">
                                         (Synopsis from Mangadex)
                                        </p>
                                </div>
                                <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/Dowman.jpg" alt="Dowman">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Dowman Sayman</h1>
                                            <h2> Author of The Voynich Hotel</h2>
                                        </div>
                                        
                                    </div>
                                    <div>
                                        <button @click="toggleM3" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--Manga4-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/OPMManga.jpg" alt="OPM" class="rounded-xl w-full object-cover" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">One Punch-Man
                                            <span class="mt-5 mb-2 block text-gray-400 text-xs">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1">
                                        <p>
                                            After rigorously training for three years, the ordinary Saitama has gained immense strength which allows him to take out anyone and anything with just one punch. He decides to put his new skill to good use by becoming a hero. However, he quickly becomes bored with easily defeating monsters, and wants someone to give him a challenge to bring back the spark of being a hero.
                                        </p>
                                        <p class="mt-3">
                                      Upon bearing witness to Saitama's amazing power, Genos, a cyborg, is determined to become Saitama's apprentice. During this time, Saitama realizes he is neither getting the recognition that he deserves nor known by the people due to him not being a part of the Hero Association. Wanting to boost his reputation, Saitama decides to have Genos register with him, in exchange for taking him in as a pupil. Together, the two begin working their way up toward becoming true heroes, hoping to find strong enemies and earn respect in the process..(Synopsis from Mangadex)
                                        </p>
                                </div>
                                <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/One.jpg" alt="One">
                                        <div class="ml-2">
                                            <h1 class="font-bold">One</h1>
                                            <h2> Author of Overlord</h2>
                                        </div>
                                        
                                    </div>
                                    <div>
                                        <button @click="toggleM4" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                <article class="bg-gray-50 rounded-xl shadow-sm hover:bg-gray-100 transition hover:duration-500 hover:shadow-md"><!--Manga5-->
                         <div class="py-6 px-5 flex">
                            <div class="flex-1 mr-8">
                                <img src="./images/Spy.jpg" alt="Spy" class="rounded-xl w-full object-cover" style="height:500px;">
                            </div>
                            <div class="flex-1 flex flex-col justify-between">
                                <header>
                                    <div>
                                        <a class="gen border-blue-400 text-blue-400 mr-1">Manga</a>
                                        <a class="gen border-red-400 text-red-400 ">Reading</a>
                                    </div>
                                    <div class="mt-4">
                                        <h1 class="text-3xl font-semibold">
                                          SPY×FAMILY
                                            <span class="mt-5 mb-2 block text-gray-400 text-xs">
                                            Review by Avas</span>
                                        </h1>

                                    </div>
                                </header>
                                <div class="text-sm mt-1">
                                        <p>
                                       Corrupt politicians, frenzied nationalists, and other warmongering forces constantly jeopardize the thin veneer of peace between neighboring countries Ostania and Westalis. In spite of their plots, renowned spy and master of disguise "Twilight" fulfills dangerous missions one after another in the hope that no child will have to experience the horrors of war.
                                        </p>
                                        <p class="mt-3">
                                          In the bustling Ostanian city of Berlint, Twilight dons the alias of "Loid Forger," an esteemed psychiatrist. However, his true intention is to gather intelligence on prominent politician Donovan Desmond, who only appears rarely in public at his sons' school: the prestigious Eden Academy. Enlisting the help of unmarried city hall clerk Yor Briar to act as his wife and adopting the curious six-year-old orphan Anya as his daughter, Loid enacts his master plan. He will enroll Anya in Eden Academy, where Loid hopes she will excel and give him the opportunity to meet Donovan without arousing suspicion.
                                        </p>
                                      
                                </div>
                                <footer class="flex items-center justify-between mt-3">
                                    <div class="text-sm text-gray-500 mt-2 flex items-center">
                                        <img class="w-12 h-12 rounded-full border-2 border-black" src="./images/Endo.png" alt="Endo">
                                        <div class="ml-2">
                                            <h1 class="font-bold">Endou Tatsuya</h1>
                                            <h2> Author of SPY×FAMILY</h2>
                                        </div>
                                        
                                    </div>
                                    <div>
                                        <button @click="toggleM5" class="text-sm bg-gray-200 rounded-full font-semibold py-2 px-3 shadow-sm hover:shadow-md hover:bg-gray-300" >Read More..</button>
                                    </div>
                                </footer>

                            </div>
                         </div>
               </article>
                  </div>
               
         </main>
          <footer class="rounded-xl bg-gray-100 flex flex-col items-center p-10 m-5">
           <a href="https://github.com/NoxMetentis"> <img src="./images/github.svg" class="h-24 w-24" alt="github logo"></a>
           <h1 class=" text-sm font-semibold text-gray-500">Check out my github profile</h1>  
            <h2 class=" text-sm font-semibold text-gray-500">This is a personal project by Me</h2>
            <div class="relative mt-4 mb-4 flex items-center  transition hover:duration-300 transform hover:scale-105 font-semibold">
                <a class="rounded-full px-10 py-2 bg-gray-300 hover:bg-gray-400  shadow-sm hover:shadow-md " href="mailto: aavashgaire@gmail.com ">Contact Me</a>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 absolute pointer-events-none" fill="none" viewBox="0 0 24 24" stroke="currentColor"  style="top: 9px; left: 9px" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                  </svg>
            </div>
            
            
            <a href="index.html" class="font-bold text-gray-500 pt-2 mt-4"><h1>Back to top</h1></a>
        </footer>
             </section>
    
   

</template>


<script>
import Modal from  './components/Modal.vue'




export default{
  name:'app',
  components:{Modal},
  data(){
    return {
      showM1: false,
       showM2: false,
        showM3: false,
         showM4: false,
          showM5: false,
      showA1: false,
      showN1: false,
      isNovel: false,
      isManga: false,
      isAnime: false,
     
    }
  },
  methods: {
    toggleM1(){
      this.showM1=!this.showM1
    },
     toggleM2(){
      this.showM2=!this.showM2
    },
     toggleM3(){
      this.showM3=!this.showM3
    },
     toggleM4(){
      this.showM4=!this.showM4
    },
     toggleM5(){
      this.showM5=!this.showM5
    },
    toggleA1(){
      this.showA1=!this.showA1
    },
      toggleN1(){
      this.showN1=!this.showN1
    },
   
    checkType(){
      if(this.selected==='Anime'){
          this.isAnime=true
          if(this.isNovel===true){
            this.isNovel= !this.isNovel
          }
          if(this.isManga===true){
            this.isManga=!this.isManga
          }
         }
            if(this.selected==='LN'){
          this.isNovel=true
          if(this.isAnime===true){
            this.isAnime= !this.isAnime
          }
          if(this.isManga===true){
            this.isManga=!this.isManga
          }
         }
         if(this.selected==='Manga'){
          this.isManga=true
          if(this.isAnime===true){
            this.isAnime= !this.isAnime
          }
          if(this.isNovel===true){
            this.isNovel=!this.isNovel
          }
         }
        
    },
  }
  
 
}
 
</script>

