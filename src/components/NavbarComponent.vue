<template>
  <nav
    class="
      border-gray-200
      px-2
      w-full
      h-20
      sm:px-4
      py-2.5
      rounded
      dark:bg-gray-900
      mx-2
    "
  >
    <div
      class="
        container
        flex flex-wrap
        justify-between
        items-center
        mx-auto
        rounded-lg
        px-2
        py-3
        shadow-md
      "
    >
      <div class="flex">
        <label class="relative block">
          <span class="sr-only">Search</span>
          <span class="absolute inset-y-0 left-0 flex items-center pl-2">
            <svg
              width="25"
              height="25"
              viewBox="0 0 25 25"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M17.9168 16.4583L22.6043 21.1458C23.021 21.5625 23.021 22.1875 22.6043 22.6041C22.396 22.8125 22.0835 22.9166 21.8752 22.9166C21.6668 22.9166 21.3543 22.8125 21.146 22.6041L16.4585 17.9166C14.896 19.0625 13.021 19.7916 10.9377 19.7916C6.04183 19.7916 2.0835 15.8333 2.0835 10.9375C2.0835 6.04165 6.04183 2.08331 10.9377 2.08331C15.8335 2.08331 19.7918 6.04165 19.7918 10.9375C19.7918 13.0208 19.0627 15 17.9168 16.4583ZM10.9377 4.16665C7.18766 4.16665 4.16683 7.18748 4.16683 10.9375C4.16683 14.6875 7.18766 17.7083 10.9377 17.7083C12.8127 17.7083 14.4793 16.9791 15.7293 15.7291C16.9793 14.4791 17.7085 12.8125 17.7085 10.9375C17.7085 7.18748 14.6877 4.16665 10.9377 4.16665Z"
                fill="black"
              />
              <mask
                id="mask0_794_3323"
                style="mask-type: alpha"
                maskUnits="userSpaceOnUse"
                x="2"
                y="2"
                width="21"
                height="21"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M17.9168 16.4583L22.6043 21.1458C23.021 21.5625 23.021 22.1875 22.6043 22.6041C22.396 22.8125 22.0835 22.9166 21.8752 22.9166C21.6668 22.9166 21.3543 22.8125 21.146 22.6041L16.4585 17.9166C14.896 19.0625 13.021 19.7916 10.9377 19.7916C6.04183 19.7916 2.0835 15.8333 2.0835 10.9375C2.0835 6.04165 6.04183 2.08331 10.9377 2.08331C15.8335 2.08331 19.7918 6.04165 19.7918 10.9375C19.7918 13.0208 19.0627 15 17.9168 16.4583ZM10.9377 4.16665C7.18766 4.16665 4.16683 7.18748 4.16683 10.9375C4.16683 14.6875 7.18766 17.7083 10.9377 17.7083C12.8127 17.7083 14.4793 16.9791 15.7293 15.7291C16.9793 14.4791 17.7085 12.8125 17.7085 10.9375C17.7085 7.18748 14.6877 4.16665 10.9377 4.16665Z"
                  fill="white"
                />
              </mask>
              <g mask="url(#mask0_794_3323)">
                <rect width="25" height="25" fill="#1F2855" />
              </g>
            </svg>
          </span>
          <input
            class="
              block
              bg-white
              w-full
              border-0
              rounded-md
              py-2
              pl-9
              pr-3
              focus:outline-none focus:border-0 focus:ring-0
              sm:text-sm
            "
            type="text"
            name="search"
          />
        </label>
      </div>

      <div class="flex items-center md:order-2">
        <button class="mr-3 relative">
          <svg
            width="20"
            height="21"
            viewBox="0 0 20 21"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M19.1668 14.6666C19.1668 15.1666 18.8335 15.5 18.3335 15.5H1.66683C1.16683 15.5 0.833496 15.1666 0.833496 14.6666C0.833496 14.1666 1.16683 13.8333 1.66683 13.8333C2.5835 13.8333 3.3335 13.0833 3.3335 12.1666V7.99998C3.3335 4.33331 6.3335 1.33331 10.0002 1.33331C13.6668 1.33331 16.6668 4.33331 16.6668 7.99998V12.1666C16.6668 13.0833 17.4168 13.8333 18.3335 13.8333C18.8335 13.8333 19.1668 14.1666 19.1668 14.6666ZM12.1668 18.4166C11.6668 19.25 10.8335 19.6666 10.0002 19.6666C9.5835 19.6666 9.16683 19.5833 8.75016 19.3333C8.3335 19.0833 8.0835 18.8333 7.8335 18.4166C7.5835 18 7.75016 17.5 8.16683 17.25C8.5835 17 9.0835 17.1666 9.3335 17.5833C9.35872 17.6085 9.38395 17.6414 9.41149 17.6773L9.4115 17.6773C9.47493 17.7599 9.55062 17.8585 9.66683 17.9166C10.0835 18.1666 10.5835 18 10.8335 17.5833C11.0835 17.1666 11.5835 17.0833 12.0002 17.25C12.4168 17.4166 12.4168 18 12.1668 18.4166ZM15.0002 12.1666C15.0002 12.75 15.1668 13.3333 15.4168 13.8333H4.5835C4.8335 13.3333 5.00016 12.75 5.00016 12.1666V7.99998C5.00016 5.24998 7.25016 2.99998 10.0002 2.99998C12.7502 2.99998 15.0002 5.24998 15.0002 7.99998V12.1666Z"
              fill="black"
            />
            <mask
              id="mask0_794_3334"
              style="mask-type: alpha"
              maskUnits="userSpaceOnUse"
              x="0"
              y="1"
              width="20"
              height="19"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M19.1668 14.6666C19.1668 15.1666 18.8335 15.5 18.3335 15.5H1.66683C1.16683 15.5 0.833496 15.1666 0.833496 14.6666C0.833496 14.1666 1.16683 13.8333 1.66683 13.8333C2.5835 13.8333 3.3335 13.0833 3.3335 12.1666V7.99998C3.3335 4.33331 6.3335 1.33331 10.0002 1.33331C13.6668 1.33331 16.6668 4.33331 16.6668 7.99998V12.1666C16.6668 13.0833 17.4168 13.8333 18.3335 13.8333C18.8335 13.8333 19.1668 14.1666 19.1668 14.6666ZM12.1668 18.4166C11.6668 19.25 10.8335 19.6666 10.0002 19.6666C9.5835 19.6666 9.16683 19.5833 8.75016 19.3333C8.3335 19.0833 8.0835 18.8333 7.8335 18.4166C7.5835 18 7.75016 17.5 8.16683 17.25C8.5835 17 9.0835 17.1666 9.3335 17.5833C9.35872 17.6085 9.38395 17.6414 9.41149 17.6773L9.4115 17.6773C9.47493 17.7599 9.55062 17.8585 9.66683 17.9166C10.0835 18.1666 10.5835 18 10.8335 17.5833C11.0835 17.1666 11.5835 17.0833 12.0002 17.25C12.4168 17.4166 12.4168 18 12.1668 18.4166ZM15.0002 12.1666C15.0002 12.75 15.1668 13.3333 15.4168 13.8333H4.5835C4.8335 13.3333 5.00016 12.75 5.00016 12.1666V7.99998C5.00016 5.24998 7.25016 2.99998 10.0002 2.99998C12.7502 2.99998 15.0002 5.24998 15.0002 7.99998V12.1666Z"
                fill="white"
              />
            </mask>
            <g mask="url(#mask0_794_3334)">
              <rect y="0.5" width="20" height="20" fill="#1F2855" />
            </g>
          </svg>
          <div class="absolute -top-2 -right-2">
            <svg
              width="18"
              height="19"
              viewBox="0 0 18 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle cx="9" cy="9.5" r="9" fill="#D2000F" />
              <path
                d="M4.83573 11.592V10.512L8.97573 5.1H10.6437L6.56373 10.512L5.78373 10.272H12.4437V11.592H4.83573ZM9.44373 13.5V11.592L9.49173 10.272V8.58H10.9557V13.5H9.44373Z"
                fill="white"
              />
            </svg>
          </div>
        </button>

        <button
          type="button"
          class="
            flex
            mr-3
            text-sm
            bg-gray-800
            rounded-full
            md:mr-0
            focus:ring-0
          "
          id="user-menu-button"
          aria-expanded="false"
          data-dropdown-toggle="user-dropdown"
          data-dropdown-placement="bottom"
        >
          <div class="mx-5 text-sc-100">
            John Doe
            <span class="flex text-cb-100 text-sm">Admin</span>
          </div>
          <div class="relative">
            <img
              class="w-8 h-8 rounded-full"
              src="../assets/images/user.png"
              alt=""
            />
            <div class="absolute top-5 -right-0.5">
              <svg
                width="11"
                height="12"
                viewBox="0 0 11 12"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="5.5" cy="6" r="5.5" fill="white" />
                <circle cx="5.49986" cy="5.99998" r="3.92857" fill="#28C76F" />
              </svg>
            </div>
          </div>
        </button>
      </div>
    </div>
    <div class="relative"></div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
</style>