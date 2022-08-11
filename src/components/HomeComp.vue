<template>
  <div class="mainHomeComponent">
    <div class="container mx-auto p-5">
      <!-- navbar -->

      <div class="md:flex md:flex-row md:justify-between text-center">
        <!-- logo -->
        <div class="flex flex-row justify-center">
          <div
            class="bg-gradient-to-r from-purple-500 to-red-500 w-10 h-10 rounded-lg"
          ></div>
          <h1 class="text-3xl text-gray-600 ml-2">Logo</h1>
        </div>
        <!-- logo-ends -->
        <!-- menu -->
        <div class="mt-2">
          <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Home</a>
          <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Shop</a>
          <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Blog</a>
          <a href="#" class="text-gray-600 hover:text-purple-600 p-4"
            >Contact</a
          >
          <a
            href="#"
            class="bg-purple-500 rounded-full text-gray-50 hover:bg-purple-700 px-5 py-3"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 inline-block"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
              />
            </svg>

            Cart(0)</a
          >
        </div>
        <!-- menu-ends -->
      </div>
      <!-- navbar-ends -->

      <!-- hero-section -->

      <div class="md:flex md:flex-row mt-20">
        <div class="md:w-2/5 flex flex-col justify-center items-center">
          <h2
            class="font-serif text-5xl text-gray-600 mb-4 text-center md:self-start md:text-left"
          >
            Some Catchy Title here
          </h2>
          <p
            class="uppercase text-gray-600 tracking-wide text-center md:self-start md:text-left"
          >
            our brand tagline goes here
          </p>
          <p
            class="uppercase text-gray-600 tracking-wide text-center md:self-start md:text-left"
          >
            our brand motto goes here
          </p>
          <a
            href=""
            class="bg-gradient-to-r from-red-600 bg-pink-500 rounded-full py-4 px-8 text-gray-50 uppercase text-xl md:self-start my-5"
            >Shop Now</a
          >
        </div>

        <div class="md:w-3/5">
          <img src="../assets/images/hero-img.svg" alt="" />
        </div>
      </div>
      <!-- hero section ends -->

      <!-- mens section -->
      <div class="my-20">
        <div class="flex flex-row justify-between my-5">
          <h2 class="text-3xl">Men's Collection</h2>
          <a href="" class="text-xl flex flex-row">
            View All
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-7 w-5 ml-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M14 5l7 7m0 0l-7 7m7-7H3"
              />
            </svg>
          </a>
        </div>
        <div
          class="grid grid-flow-row fgrid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-10"
        >
          <!-- product-card1 -->

          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/men/product1.jpg"
                alt=""
              />
            </a>

            <div class="p-5">Men's T-shirt</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->
          <!-- product-card -->

          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/men/product2.jpg"
                alt=""
              />
            </a>

            <div class="p-5">Men's Pant</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->
          <!-- product-card -->

          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/men/product3.jpg"
                alt=""
              />
            </a>

            <div class="p-5">Men's shoes</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->
          <!-- product-card -->

          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/men/product4.jpg"
                alt=""
              />
            </a>

            <div class="p-5">Men's Watch</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->
        </div>
      </div>
      <!-- mens section ends -->

      <!-- womens section -->
      <div class="my-20">
        <div class="flex flex-row justify-between my-5">
          <h2 class="text-3xl">Women's Collection</h2>
          <a href="" class="text-xl flex flex-row">
            View All
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-7 w-5 ml-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M14 5l7 7m0 0l-7 7m7-7H3"
              />
            </svg>
          </a>
        </div>
        <div
          class="grid grid-flow-row fgrid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-10"
        >
          <!-- product-card -->
          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/women/product1.jpg"
                alt=""
              />
            </a>

            <div class="p-5">women's T-shirt</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->

          <!-- product-card -->
          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/women/product2.jpg"
                alt=""
              />
            </a>

            <div class="p-5">women's red dress</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->

          <!-- product-card -->
          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/women/product3.jpg"
                alt=""
              />
            </a>

            <div class="p-5">women's Skirt</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->

          <!-- product-card -->
          <div class="shadow-lg rounded-lg">
            <a href="">
              <img
                class="rounded-t-md"
                src="../assets/images/products/women/product4.jpg"
                alt=""
              />
            </a>

            <div class="p-5">women's kattu</div>
            <div class="flex flex-row my-3">
              <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
              <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
              <div
                class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"
              ></div>
            </div>
            <div class="flex flex-row my-3">
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                XXL
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                L
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                M
              </div>
              <div
                class="border-2 border-gray-300 text-gray-400 rounded-md text-xs py-1 px-2"
              >
                S
              </div>
            </div>

            <div class="flex flex-row justify-between mb-4">
              <a
                href=""
                class="bg-gradient-to-r from-red-500 text-gray-50 text-sm to-pink-500 rounded-full py-2 px-4 ml-2 flex flex-row hover:from-pink-600 hover:to-pink-600"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Add to cart
              </a>
              <a
                href=""
                class="bg-purple-600 text-gray-50 rounded-full mr-2 py-2 px-4 flex flex-row text-sm hover:from-pink-600 hover:bg-purple-700"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  F
                  class="h-5 w-5 ml-1 mr-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  />
                </svg>

                view Detail
              </a>
            </div>
          </div>
          <!-- product-card ends -->
        </div>
      </div>
      <!-- womens section ends -->

      <div class="shadow-lg my-20 rounded-lg flex flex-row">
        <div
          class="lg:w-3/5 bg-gradient-to-r from-black lg:via-purple-900 lg:to-white p-10 to-purple-900"
        >
          <div class="lg:w-1/2">
            <h2 class="text-gray-50 text-2xl font-extrabold mb-4 text-center">
              Suscribe to get our offers first
            </h2>
            <p class="mb-4 leading-relaxed text-gray-50 text-center">
              Want to hear from us when we have new offers? Sign up for our
              newsletter and we'll email you every time we have new sale offers.
            </p>
          </div>

          <input
            type="email"
            placeholder="Enter email address"
            class="bg-gray-600 text-gray-200 placeholder-gray-400 px-4 py-3 w-full rounded-lg"
          />
          <button
            type="submit"
            class="bg-red-600 py-3 rounded-lg w-full text-gray-50 mt-5"
          >
            Suscribe
          </button>
        </div>
        <div class="w-full lg:w-2/5 lg:flex lg:flex-row hidden">
          <img
            src="../assets/images/subscribe-banner.png"
            class="h-96"
            alt=""
          />
        </div>
      </div>

      <!-- footer -->
      <footer class="text-gray-600 body-font">
        <div
          class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col"
        >
          <a
            class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"
              />
            </svg>
            <span class="ml-3 text-xl">Brandtech</span>
          </a>
          <p
            class="text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-200 sm:py-2 sm:mt-0 mt-4"
          >
            © 2022 shop —
            <a
              href="https://twitter.com/knyttneve"
              class="text-gray-600 ml-1"
              rel="noopener noreferrer"
              target="_blank"
              >@brandtech</a
            >
          </p>
          <span
            class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start"
          >
            <a class="text-gray-500">
              <svg
                fill="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path
                  d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="currentColor"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="0"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  stroke="none"
                  d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"
                ></path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
          </span>
        </div>
      </footer>
      <!-- footerends -->
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeComp",
};
</script>

<style></style>
