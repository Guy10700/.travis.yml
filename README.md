# .travis.yml
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="./styles/mon_css.css">
    <link rel="stylesheet" href="./styles/tailwind.css">
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<div class="flex space-x-2 mt-5 border border-gray-200 shadow-2xl m-32 rounded-lg">
    <div class="c1 bg-blue-400 h-screen  w-full">
        <p class="spacing-x-2">Bienvenue sur MyBook</p>

    </div>

    <div class=" bg-white h-screen w-1/2 relative">
        <img src="./img/CornerPlants.jpg" alt="plant" class="w-24 absolute right-0 mr-5 mt-5">

        <!--      Debut  Image femme-->
        <div CLASS="relative w-24 mt-20 m-auto">
            <img src="./img/Head-Front-Rad@2x.png" alt="image de femme africaine">
        </div>
        <!--      Fin  Image femme-->

        <!--      Debut nom projet-->
        <div CLASS="relative w-24 mt-3 m-auto mb-3">
            <p CLASS="font-bold tracking-wider">MYBOOK</p>
        </div>
        <!--      FIN nom projet-->


        <!--        INPUT BLOCK N 1-->
        <div class="relative flex w-64 flex-wrap items-stretch m-auto mb-3 ">
            <span class="z-10 h-full leading-snug font-normal absolute text-center text-gray-400 absolute bg-transparent rounded text-base items-center justify-center w-8 pl-3 py-3">
                <i class="far fa-envelope"></i>
            </span>
            <input type="text" placeholder="myiuc@gmail.com"
                   class="px-3 py-3 placeholder-gray-400 text-gray-700 relative bg-white bg-white rounded-full text-sm border border-gray-400 outline-none focus:outline-none focus:ring-2 focus:ring-purple-600 focus:border-transparent w-full pl-10"/>
        </div>
        <!--      fin  INPUT BLOCK N 1-->


        <!--      Debut  INPUT BLOCK N 2-->
        <div class="relative flex w-64 flex-wrap items-stretch mb-3 m-auto">
            <span class="z-10 h-full leading-snug font-normal absolute text-center text-gray-400 absolute bg-transparent rounded text-base items-center justify-center w-8 pl-3 py-3">
                <i class="far fa-envelope"></i>
            </span>
            <input type="text" placeholder="Password"
                   class="px-3 py-3 placeholder-gray-400 text-gray-700 relative bg-white bg-white rounded-full text-sm border border-gray-400 outline-none focus:outline-none focus:ring-2 focus:ring-purple-600 focus:border-transparent w-full pl-10"/>
        </div>
        <!--      FIN INPUT BLOCK N 2-->



        <!--      Debut  INPUT BLOCK N 3-->
        <div class="relative flex w-64 flex-wrap items-stretch mb-3 m-auto">
            <span class="z-10 h-full leading-snug font-normal absolute text-center text-gray-400 absolute bg-transparent rounded text-base items-center justify-center w-8 pl-3 py-3">
                <i class="far fa-envelope"></i>
            </span>
            <input type="text" placeholder="Re-saisir Password"
                   class="px-3 py-3 placeholder-gray-400 text-gray-700 relative bg-white bg-white rounded-full text-sm border border-gray-400 outline-none focus:outline-none focus:ring-2 focus:ring-purple-600 focus:border-transparent w-full pl-10"/>
        </div>

        <!--      FIN INPUT BLOCK N 3-->


        <button class="mb-8 mt-10 block text-white mx-auto bg-blue-500 pl-8 pr-8 pt-2 pb-2 rounded-full m-auto focus:outline-none ">Incription
        </button>
    </div>
</div>
</body>
</html>
