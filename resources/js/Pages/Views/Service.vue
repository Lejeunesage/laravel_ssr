<script setup>
import NavbarLayout from '@/Layouts/NavbarLayout.vue';
import Footer from '@/Layouts/Footer.vue';

import TextInput from '@/Components/TextInput.vue';
import InputLabel from '@/Components/InputLabel.vue';
import PrimaryButton from '@/Components/PrimaryButton.vue'; 
import ArrowIcon from '@/Components/ArrowIcon.vue';
import { Head, Link, useForm } from '@inertiajs/vue3';



</script>

<template>
    <div class="bg-dots-darker">
        <NavbarLayout >
            <Head title="Service" />

            <div class="mx-auto max-w-screen-xl px-4 md:px-6 mt-[4rem] md:mt-[8rem] py-2.5 ">
                <h2 class="text-3xl mb-[1rem] text-center font-semibold">Profitez des occasions d'affaires d'une économie numérique mondiale.</h2>

                <p class="mb-[.5rem] text-center">Comblez tous vos besoins en technologie et en marketing numérique avec des experts sous un même toit. </p>
                
                <p class="mb-[1rem] text-center">Chez Teroc, nous privilégions:</p>

                <ul class="mb-[1rem] list-disc px-10">
                    <li>Une écoute attentive de vos besoins</li>
                    <li>Des solutions et des recommandations muries et personnalisées</li>
                    <li>Une geston de projet minutieuse, rigoureuse, agile et maitrisée</li>
                </ul>
            </div>   

            <div class="flex flex-col md:flex-row items-center gap-10 justify-center px-10 my-[2rem]">
                <a  class="border px-[3.3rem] py-5 text-white bg-[orange] hover:bg-orange-400" href="">Solutions Technologiques</a>
                <a class="border p-5 text-white bg-[orange] hover:bg-orange-400" href="">Solutions En Marketing Numérique</a>
            </div>

            <div class="bg-clr-amour  bg-dots-darker p-[2rem] pb-[5rem] mt-[5rem] ">
            <div  class="" >
                    <h3 class="text-2xl mb-[1rem] text-center font-semibold">Solutions Technologiques</h3>

                    <div class="grid md:grid-cols-3 gap-10 mx-auto max-w-screen-lg">
                        <div class="text-center mt-[3rem]   border p-10 shadow bg-white ">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">
                                <img class="w-[15rem]" src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                        <div class=" border p-10 shadow  text-center mt-[3rem]   bg-white">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">
                                <img class="w-[15rem]"  src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                        <div class=" border p-10 shadow  text-center mt-[3rem]  bg-white">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">

                                <img  class="w-[15rem]"  src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                    </div>


            </div>
            </div>
            <div class=" p-[3rem]  ">
            <div  class=" " >
                    <h3 class="text-2xl mb-[1rem] text-center font-semibold">Solution en Marketing Numérique</h3>

                    <div class="grid md:grid-cols-3 gap-10 mx-auto max-w-screen-lg">
                        <div class="text-center mt-[3rem]   border p-10 shadow bg-white ">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">
                                <img class="w-[15rem]" src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                        <div class=" border p-10 shadow  text-center mt-[3rem]   bg-white">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">
                                <img class="w-[15rem]"  src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                        <div class=" border p-10 shadow  text-center mt-[3rem]  bg-white">
                            <div class="flex justify-center items-center flex-col gap-2 mb-5">

                                <img  class="w-[15rem]"  src="@/../../public/images/capture-1.png" alt="">
                                <h4 class="font-semibold ">Developpement logiciels et applications</h4>
                                <p>Développer une application et des logiciels sur mesure pour résoudre un problème spécifique ou simplement offrir un nouveau...</p>
                            </div>
                            <a class="flex " href="#">Lire la suite 
                                <ArrowIcon/>
                            </a>
                        </div>
                    </div>


            </div>
            </div>
            <div class=" mt-10 px-5">
                <div class= "flex justify-center">
                    <h3 class="text-2xl font-semibold text-center md:w-1/2">Et vous! Quel est votre défi? Nous sommes impatients de vous entendre et de vous aider. </h3>
                </div>
                <div>
                    <form action="" class="max-w-xl mx-auto mt-20 mb-20">
                        <div class="">
                            <div class="flex flex-col">
                                <label for="">Votre nom complet*</label>
                                <input
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4 " 
                                type="text">
                            </div>
                            <div class="flex flex-col">
                                <label for="">Votre numéro de téléphone*</label>
                                <input
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4" 
                                type="text">
                            </div>
                        </div>
                        <div class=" ">
                            <div class="flex flex-col">
                                <label for="">Sélectionner un sujet*</label>
                                <select 
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4 " 
                                >
                                    <option value=""></option>
                                    <option value="">Beauté</option>
                                    <option value="">E-commerce</option>
                                    <option value="">Cosmétique</option>
                                    
                                </select>
                            </div>
                            <div class="flex flex-col">
                                <label for="">Sélectionner un budbet (pour marketing)*</label>
                                <select 
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4 " 
                                >
                                    <option value=""></option>
                                    <option value="">1000€</option>
                                    <option value="">1500€</option>
                                    <option value="">2000€</option>
                                    
                                </select>
                                
                            </div>
                        </div>
                        <div class="">
                            <div class="flex flex-col">
                                <label for="">Adresse e-mail*</label>
                                <input
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4 " 
                                type="text">
                            </div>
                            <div class="flex flex-col">
                                <label for="">Message et site web</label>
                                <textarea 
                                class="border-gray-300 focus:border-indigo-500 focus:ring-indigo-500 rounded-md shadow-sm mt-1 mb-4 " 
                                ></textarea>
        
                            </div>
                        </div>
                        
                        
                    </form>
                </div>
            </div>
        
    
            <Footer></Footer>
        </NavbarLayout>
    </div>      

</template>



