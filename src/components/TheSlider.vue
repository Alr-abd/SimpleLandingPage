<template>
  <svg class="hidden">
      <symbol id="search" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M11 19C15.4183 19 19 15.4183 19 11C19 6.58172 15.4183 3 11 3C6.58172 3 3 6.58172 3 11C3 15.4183 6.58172 19 11 19Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M21 21L16.65 16.65" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="menu" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
         <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
      </symbol>
      <symbol id="Date" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M19 4H5C3.89543 4 3 4.89543 3 6V20C3 21.1046 3.89543 22 5 22H19C20.1046 22 21 21.1046 21 20V6C21 4.89543 20.1046 4 19 4Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M16 2V6" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M8 2V6" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M3 10H21" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="Time" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M12 6V12L16 14" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="Location" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M21 10C21 17 12 23 12 23C12 23 3 17 3 10C3 7.61305 3.94821 5.32387 5.63604 3.63604C7.32387 1.94821 9.61305 1 12 1C14.3869 1 16.6761 1.94821 18.364 3.63604C20.0518 5.32387 21 7.61305 21 10Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M12 13C13.6569 13 15 11.6569 15 10C15 8.34315 13.6569 7 12 7C10.3431 7 9 8.34315 9 10C9 11.6569 10.3431 13 12 13Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
       </symbol>
       <symbol id="World" viewBox="0 0 40 37" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M19.4942 36.2389C14.3083 36.2172 9.34336 34.293 5.68876 30.8884C2.03417 27.4839 -0.0116824 22.877 5.01863e-05 18.0785C0.0117828 13.2801 2.08014 8.68182 5.75135 5.2926C9.42256 1.90339 14.3968 0 19.5828 0C24.7688 0 29.7431 1.90339 33.4143 5.2926C37.0855 8.68182 39.1539 13.2801 39.1656 18.0785C39.1773 22.877 37.1315 27.4839 33.4769 30.8884C29.8223 34.293 24.8574 36.2172 19.6714 36.2389H19.4942ZM14.7249 31.9029C12.0376 28.3583 10.3804 24.2339 9.91238 19.9259H4.03661C4.41265 22.6529 5.6163 25.2254 7.50802 27.3452C9.39974 29.465 11.9021 31.0453 14.7249 31.9029ZM24.4454 31.9029C27.2674 31.0457 29.7691 29.4663 31.6607 27.3476C33.5524 25.2288 34.7565 22.6575 35.1337 19.9316H29.261C28.7978 24.2389 27.1389 28.3638 24.4454 31.9029ZM19.4649 31.6534L19.5836 31.7774L19.7022 31.6534C22.8169 28.3613 24.7796 24.2728 25.3315 19.9273H13.8434C14.3942 24.2717 16.3541 28.3598 19.4649 31.6534ZM35.1337 16.3085C34.7576 13.5816 33.554 11.0091 31.6622 8.88924C29.7705 6.76942 27.2682 5.18911 24.4454 4.33151C27.133 7.87608 28.7907 12.0004 29.2594 16.3085H35.1337ZM25.3299 16.3085C24.7796 11.9638 22.8191 7.87543 19.7069 4.58246L19.5867 4.45698L19.4711 4.58246C16.3733 7.88419 14.4139 11.968 13.845 16.3085H25.3299ZM9.91238 16.3085C10.3743 11.9987 12.0332 7.87273 14.728 4.33151C11.906 5.18978 9.40466 6.77038 7.5138 8.89015C5.62294 11.0099 4.41998 13.5821 4.04431 16.3085H9.91238Z" fill="#091119"/>
      </symbol>
      <symbol id="Twi" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M32.5834 4.25009C31.2267 5.20701 29.7247 5.93891 28.135 6.41759C27.2818 5.43656 26.1479 4.74123 24.8867 4.42565C23.6254 4.11006 22.2976 4.18945 21.083 4.65306C19.8683 5.11668 18.8253 5.94215 18.0951 7.01785C17.3648 8.09355 16.9826 9.36756 17 10.6676V12.0843C14.5104 12.1488 12.0435 11.5967 9.81895 10.477C7.59441 9.35728 5.6813 7.70482 4.25002 5.66675C4.25002 5.66675 -1.41665 18.4168 11.3334 24.0834C8.41577 26.0639 4.94016 27.0569 1.41669 26.9168C14.1667 34.0001 29.75 26.9168 29.75 10.6251C29.7487 10.2305 29.7108 9.83684 29.6367 9.44925C31.0825 8.02337 32.1029 6.2231 32.5834 4.25009Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="In" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M22.6667 11.3335C24.921 11.3335 27.083 12.229 28.6771 13.8231C30.2712 15.4171 31.1667 17.5792 31.1667 19.8335V29.7502H25.5V19.8335C25.5 19.082 25.2015 18.3614 24.6702 17.83C24.1388 17.2987 23.4181 17.0002 22.6667 17.0002C21.9152 17.0002 21.1946 17.2987 20.6632 17.83C20.1319 18.3614 19.8334 19.082 19.8334 19.8335V29.7502H14.1667V19.8335C14.1667 17.5792 15.0622 15.4171 16.6563 13.8231C18.2503 12.229 20.4123 11.3335 22.6667 11.3335Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M8.49998 12.75H2.83331V29.75H8.49998V12.75Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M5.66665 8.50016C7.23145 8.50016 8.49998 7.23164 8.49998 5.66683C8.49998 4.10202 7.23145 2.8335 5.66665 2.8335C4.10184 2.8335 2.83331 4.10202 2.83331 5.66683C2.83331 7.23164 4.10184 8.50016 5.66665 8.50016Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="Insta" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect width="40" height="40" fill="white"/>
        <path d="M28.3333 3.3335H11.6666C7.06427 3.3335 3.33331 7.06446 3.33331 11.6668V28.3335C3.33331 32.9359 7.06427 36.6668 11.6666 36.6668H28.3333C32.9357 36.6668 36.6666 32.9359 36.6666 28.3335V11.6668C36.6666 7.06446 32.9357 3.3335 28.3333 3.3335Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M26.6667 18.95C26.8724 20.3371 26.6355 21.7537 25.9896 22.9984C25.3438 24.243 24.3219 25.2524 23.0694 25.8828C21.8169 26.5132 20.3974 26.7327 19.013 26.5099C17.6286 26.2871 16.3496 25.6335 15.3581 24.6419C14.3665 23.6504 13.7129 22.3715 13.4901 20.987C13.2674 19.6026 13.4868 18.1832 14.1172 16.9306C14.7477 15.6781 15.757 14.6562 17.0017 14.0104C18.2463 13.3646 19.6629 13.1277 21.05 13.3333C22.4649 13.5432 23.7748 14.2025 24.7862 15.2139C25.7976 16.2253 26.4569 17.5351 26.6667 18.95Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M29.1667 10.8335H29.183" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>
      <symbol id="F" viewBox="0 0 18 32" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M17 1H12.6364C10.7075 1 8.85767 1.79018 7.49377 3.1967C6.12987 4.60322 5.36364 6.51088 5.36364 8.5V13H1V19H5.36364V31H11.1818V19H15.5455L17 13H11.1818V8.5C11.1818 8.10218 11.3351 7.72064 11.6078 7.43934C11.8806 7.15804 12.2506 7 12.6364 7H17V1Z" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </symbol>




      <symbol id="Android" viewBox="0 0 49 44" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g clip-path="url(#clip0_190_276)">
        <path d="M31.8491 43.9999C31.1998 43.9991 30.5775 43.7881 30.1184 43.4131C29.6593 43.0381 29.401 42.5298 29.4 41.9995V37.9898H19.6V41.9995C19.6 42.5312 19.3414 43.0412 18.8811 43.4171C18.4208 43.7931 17.7964 44.0044 17.1455 44.0044C16.4945 44.0044 15.8701 43.7931 15.4098 43.4171C14.9495 43.0412 14.6909 42.5312 14.6909 41.9995V37.9898H12.2473C10.9526 37.9894 9.71076 37.5704 8.79324 36.8243C7.87572 36.0782 7.35716 35.0657 7.35091 34.0083V15.9809C7.3487 13.7626 7.99256 11.5758 9.2293 9.60086C10.4661 7.62597 12.2602 5.9197 14.4636 4.62296L12.9782 3.4245C12.516 3.0515 12.2541 2.54382 12.2502 2.01312C12.2463 1.48243 12.5006 0.972197 12.9573 0.594675C13.4139 0.217152 14.0355 0.00326264 14.6852 5.98058e-05C15.3349 -0.00314303 15.9596 0.204603 16.4218 0.577596L18.8709 2.55424C18.9299 2.60126 18.9857 2.65083 19.0382 2.70275C22.5831 1.7356 26.4169 1.7356 29.9618 2.70275C30.0144 2.65089 30.0702 2.60132 30.1291 2.55424L32.5782 0.577596C32.8046 0.383821 33.0763 0.229124 33.3772 0.122668C33.6781 0.0162128 34.0021 -0.0398369 34.33 -0.042161C34.6579 -0.044485 34.9831 0.0069637 35.2862 0.109138C35.5894 0.211313 35.8643 0.362135 36.0948 0.552672C36.3253 0.74321 36.5066 0.969588 36.628 1.2184C36.7494 1.46721 36.8085 1.73339 36.8017 2.00118C36.7949 2.26898 36.7223 2.53293 36.5884 2.77741C36.4544 3.02189 36.2618 3.24193 36.0218 3.4245L34.5345 4.62444C36.7383 5.92081 38.5329 7.62671 39.7703 9.60133C41.0076 11.5759 41.6523 13.7626 41.6509 15.9809V34.0083C41.648 35.0675 41.1309 36.0827 40.2131 36.831C39.2952 37.5793 38.0514 37.9998 36.7545 38.0002H34.3V42.0099C34.2957 42.5386 34.0356 43.0446 33.5765 43.4173C33.1174 43.7901 32.4965 43.9995 31.8491 43.9999ZM12.2491 17.9857V34.0083L36.7527 33.9979V17.9887L12.2491 17.9857ZM13.8455 11.04C13.2063 11.9562 12.7503 12.9498 12.4945 13.9834H36.5055C36.2487 12.9503 35.792 11.9572 35.1527 11.0415C34.9489 11.3078 34.6713 11.5313 34.3422 11.6938C34.0131 11.8563 33.6418 11.9532 33.2584 11.9768C32.8749 12.0004 32.4901 11.95 32.1349 11.8296C31.7797 11.7092 31.4642 11.5223 31.2139 11.2839C30.9635 11.0455 30.7854 10.7623 30.6938 10.4572C30.6023 10.1522 30.5999 9.83378 30.6869 9.52783C30.7738 9.22187 30.9477 8.93693 31.1945 8.69603C31.4412 8.45513 31.7539 8.26504 32.1073 8.14112C29.9419 6.74076 27.261 5.97881 24.4991 5.97881C21.7372 5.97881 19.0563 6.74076 16.8909 8.14112C17.2445 8.2649 17.5575 8.45495 17.8045 8.69588C18.0515 8.93681 18.2256 9.22185 18.3127 9.52794C18.3998 9.83404 18.3975 10.1526 18.3059 10.4578C18.2143 10.763 18.036 11.0463 17.7855 11.2848C17.5349 11.5233 17.2192 11.7102 16.8637 11.8305C16.5083 11.9508 16.1232 12.0011 15.7396 11.9773C15.3559 11.9534 14.9846 11.8562 14.6555 11.6933C14.3265 11.5305 14.0489 11.3067 13.8455 11.04ZM46.5455 29.9985C45.8972 29.9986 45.2753 29.7886 44.8162 29.4147C44.3572 29.0409 44.0983 28.5336 44.0964 28.0041V15.9779C44.0964 15.4472 44.3545 14.9382 44.814 14.5629C45.2734 14.1876 45.8966 13.9767 46.5464 13.9767C47.1961 13.9767 47.8193 14.1876 48.2788 14.5629C48.7382 14.9382 48.9964 15.4472 48.9964 15.9779V27.9967C48.9966 28.2596 48.9334 28.52 48.8103 28.763C48.6872 29.0059 48.5067 29.2267 48.279 29.4126C48.0514 29.5986 47.7811 29.746 47.4837 29.8466C47.1862 29.9471 46.8674 29.9987 46.5455 29.9985ZM2.44545 29.9985C1.79655 29.9978 1.17454 29.7867 0.716036 29.4116C0.257529 29.0365 -7.15284e-07 28.5282 0 27.9981L0 15.9779C9.68397e-09 15.4472 0.258124 14.9382 0.717588 14.5629C1.17705 14.1876 1.80022 13.9767 2.45 13.9767C3.09978 13.9767 3.72295 14.1876 4.18241 14.5629C4.64188 14.9382 4.9 15.4472 4.9 15.9779V27.9967C4.90024 28.2596 4.83701 28.52 4.71392 28.763C4.59084 29.0059 4.41031 29.2267 4.18268 29.4126C3.95504 29.5986 3.68476 29.746 3.3873 29.8466C3.08983 29.9471 2.77102 29.9987 2.44909 29.9985H2.44545Z" fill="#091119"/>
        </g>
        <defs>
        <clipPath id="clip0_190_276">
        <rect width="49" height="44" fill="white"/>
        </clipPath>
        </defs>
      </symbol>
      <symbol id="MacOs" viewBox="0 0 90 112" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect width="90" height="112" rx="18" fill="#D9D9D9"/>
      </symbol>
      <symbol id="Ios" viewBox="0 0 54 44" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M31.3453 40.0983L28.2189 39.6183C27.7294 39.5474 27.3984 39.504 27.1781 39.4891L27 39.4823L22.7572 40.1063C21.924 40.2347 21.08 40.3111 20.2325 40.3348L19.7542 40.3211C16.618 40.1508 13.6038 38.264 11.2741 35.0045C9.10961 31.9187 7.94037 28.4362 7.8756 24.8823C7.73652 21.7063 9.03432 18.5994 11.5224 16.152C12.5409 15.1757 13.7974 14.3827 15.2121 13.8232C16.6268 13.2636 18.1687 12.9498 19.7402 12.9017C19.8636 12.9017 19.9894 12.9017 20.1175 12.9017C20.9015 12.9051 21.6846 12.9467 22.4626 13.0263C23.1639 13.096 23.9269 13.1908 24.7811 13.32C25.1472 13.3725 25.7854 13.4731 26.2637 13.5543L26.965 13.6743C27.0858 13.6434 27.2091 13.619 27.3338 13.6011L29.2217 13.2914C29.7323 13.2103 30.2316 13.1383 30.7099 13.0765L31.2934 13.0034C32.1057 12.8999 32.9258 12.8426 33.7479 12.832C36.2016 12.7207 38.6302 13.283 40.6456 14.4289C42.6609 15.5748 44.1465 17.2382 44.8649 19.1531C45.0354 19.5378 45.0426 19.958 44.8855 20.3465C44.7283 20.7349 44.4159 21.0692 43.9981 21.296C41.6754 22.56 40.4916 23.7657 40.4916 24.88C40.5299 25.3048 40.6835 25.7174 40.9413 26.088C41.1992 26.4586 41.5548 26.7779 41.9826 27.0228C42.1775 27.1611 42.3935 27.3051 42.6839 27.4903L43.8059 28.1885C43.9189 28.2635 44.0271 28.3433 44.1299 28.4274C44.4027 28.6213 44.6206 28.8611 44.7688 29.1302C44.917 29.3993 44.9919 29.6913 44.9883 29.9863C44.9883 31.2834 43.4006 33.8617 41.2153 36.1188C38.6219 38.7954 35.8981 40.3314 33.7395 40.3314C32.9345 40.3115 32.1333 40.2335 31.3453 40.0983ZM28.9146 35.9931L32.0536 36.4754C32.7647 36.5783 33.2093 36.6343 33.5011 36.6571L33.7535 36.6674C34.7522 36.6674 36.4423 35.376 38.0623 33.3771C38.7624 32.5072 39.3962 31.603 39.96 30.6697L40.075 30.4754L39.6248 30.192C39.4326 30.0663 39.2363 29.9325 39.0119 29.7725C38.0962 29.1909 37.351 28.4503 36.8306 27.6046C36.3102 26.7588 36.0276 25.8293 36.0033 24.8834C36.0673 23.8193 36.4197 22.7799 37.0352 21.8399C37.6507 20.9 38.514 20.0827 39.5631 19.4468L39.9586 19.176L39.8941 19.08C39.3289 18.2704 38.502 17.6027 37.5033 17.1495C36.5047 16.6963 35.3727 16.475 34.2304 16.5097L33.7549 16.5017C32.9744 16.5207 32.1966 16.5868 31.428 16.6994L30.9946 16.7588L30.0731 16.8937C30.0549 16.8937 28.0744 17.2365 27.2847 17.328L27.0042 17.3531C26.784 17.3524 26.5642 17.3351 26.3478 17.3017L24.2664 16.9737L23.4248 16.8503C22.8638 16.7714 22.3714 16.712 21.9198 16.6685C21.3207 16.6047 20.7174 16.57 20.1133 16.5645H19.8762C18.8747 16.6013 17.8948 16.8144 17.004 17.1893C16.1132 17.5642 15.3326 18.0918 14.7161 18.736C13.0858 20.5008 12.2579 22.672 12.3737 24.8788C12.4599 27.6099 13.3242 30.2873 14.8984 32.6994C16.5044 35.1748 18.482 36.6548 20.1876 36.6628L20.5789 36.648C21.0726 36.6103 21.8918 36.5074 23.0082 36.3463L26.0701 35.8891C26.3761 35.8428 26.6861 35.8164 26.9972 35.8103C27.6419 35.8222 28.2839 35.8834 28.9146 35.9931ZM26.9187 10.992C26.4079 10.9718 25.9209 10.8102 25.5383 10.5337C25.1557 10.2573 24.9005 9.88273 24.8148 9.47197C24.2018 6.55655 27.9033 3.66626 31.4967 3.66626C32.0805 3.66605 32.6413 3.85115 33.0603 4.1823C33.4792 4.51345 33.7234 4.96458 33.7409 5.43997C33.7741 6.15489 33.6312 6.86798 33.3207 7.53717C33.0101 8.20635 32.5382 8.81807 31.9328 9.33621C31.3273 9.85435 30.6006 10.2684 29.7956 10.554C28.9905 10.8395 28.1234 10.9908 27.2455 10.9988C27.1403 10.9988 27.0295 10.9965 26.9187 10.992Z" fill="#091119"/>
      </symbol>
      <symbol id="Window" viewBox="0 0 42 39" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g clip-path="url(#clip0_190_281)">
        <path d="M39.015 39C38.8592 38.9998 38.7037 38.9888 38.5496 38.967L2.82611 33.3673C2.04367 33.2538 1.32987 32.8839 0.812177 32.3238C0.294487 31.7636 0.00662522 31.0496 0 30.3094L0 8.70271C0.007714 7.96128 0.295629 7.24629 0.81282 6.6842C1.33001 6.12211 2.04315 5.74914 2.82611 5.63127L38.5496 0.033045C38.7047 0.011226 38.8614 0.000192323 39.0182 3.48174e-05C39.4131 -0.00181538 39.8044 0.0700915 40.1692 0.211537C40.534 0.352982 40.8649 0.561117 41.1425 0.823729C41.4201 1.08634 41.6388 1.39814 41.7858 1.74084C41.9327 2.08354 42.005 2.45023 41.9984 2.8194V36.1807C42.0048 36.55 41.9323 36.9169 41.785 37.2597C41.6378 37.6025 41.4188 37.9143 41.1409 38.177C40.863 38.4396 40.5318 38.6477 40.1667 38.789C39.8017 38.9303 39.4101 39.0021 39.015 39ZM19.9496 21.4566V32.0859L37.8018 34.9203L37.8419 21.4566H19.9496ZM4.17256 21.4566V29.5861L15.7578 31.4257V21.4566H4.17256ZM37.8916 4.09629L19.9496 6.92316V17.5374H37.8531L37.8916 4.09629ZM15.7498 7.58487L4.19502 9.40343L4.18058 17.5359H15.7498V7.58487Z" fill="#212121"/>
        </g>
        <defs>
        <clipPath id="clip0_190_281">
        <rect width="42" height="39" fill="white"/>
        </clipPath>
        </defs>
      </symbol>










  </svg>
<div>
  <div class="w-full h-auto">
    <header class="mainshodow z-[1000] fixed bg-[#FFFFFF] w-full xl:w-[1440px] xl:ml-[33px] h-[44px] md:h-[98px] flex items-center justify-between md:justify-normal" >
      <div class="flex items-center justify-center">
        <img src="./../Pic/5f2ec6d494f394978131ba14a690d793.png" alt="logo" class="w-[37px] md:w-[100px] h-[38px] md:h-[102px] my-[3px] md:my-0 mr-[41px] md:mr-[40px] xl:mr-[172px]">
        <span class="md:hidden font-vazir font-semibold mr-0">آیندگان برتر</span>
      </div>
      <ul class="hidden md:flex items-center mr-[40px] md:w-[600px] lg:w-[532px] justify-between md:space-x-1">
        <li>
            <a href="#">
              <span class="textSpan font-vazir">دوره آموزشی</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan font-vazir">مقالات</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan font-vazir">پرسش و پاسخ</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan font-vazir">مدرسان</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan font-vazir">درباره ما</span>
            </a>
        </li>
      </ul>
      <button @click="opendivOfHeaderMb" class="btnOfHeaderMb md:hidden w-[30px] h-[30px] ml-[44px] flex justify-center items-center">
        <svg class="w-[3rem] h-[1.5rem] text-[#001A72]">
          <use href="#menu"></use>
        </svg>
      </button>
      <a href="#" class="hidden md:block">
        <span class="w-[36px] h-[31px] md:mr-[22px] xl:mr-[125px] mr-[80px] font-vazir font-bold text-[20px]">ورود</span>
      </a>
      <div class="hidden md:flex items-center mr-[30px] relative">
        <input id="inputOfSearchInHeader" type="text" class="customPlace pr-[15px] w-[163px] h-[46px] rounded-[13px]" placeholder="جستجو....">
        <svg class="w-6 h-6 absolute left-[7px] top-[11px] cursor-pointer">
          <use href="#search"></use>
        </svg>
      </div>
      <button class="btnOfHeader hidden md:block mr-[20px] w-[119px] h-[46px] rounded-[13px] md:ml-[10px] xl:ml-0">
        <span class="spanOfHeader font-vazir font-bold text-[20px]">عضویت</span>
      </button>
    </header>
    <!-- Empty Div -->
    <div class="w-full h-[44px] md:h-[98px]"></div>
    <!-- DivMenu Of Header For Mb  -->
    <div v-if="divOfHeaderMb === true" class="divMenuOfHeaderMb fixed md:hidden w-full h-[400px] bg-[#EAEDF8]">
      <ul class="pt-[40px] mb-[25px] w-full mr-[25px] justify-start space-y-[25px]">
        <li>
            <a href="#">
              <span class="textSpan2 font-vazir">دوره آموزشی</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan2 font-vazir">مقالات</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan2 font-vazir">پرسش و پاسخ</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan2 font-vazir">مدرسان</span>
            </a>
        </li>
        <li>
            <a href="#">
              <span class="textSpan2 font-vazir">درباره ما</span>
            </a>
        </li>
      </ul>
      <div class="w-full flex justify-center items-center">
        <button style="border-color: black !important;" class="w-[314px] sm:w-[90%] h-[42px] border border-solid mx-[25px] mb-[44px] font-vazir font-black text-[20px]" >
          پنل کاربری
        </button>
      </div>
    </div>
    <main class="w-full">
      <!-- Task 1 -->
    <div class="w-full flex justify-center">
      <div class="w-[305px] md:w-[600px] xl:w-[1223px] h-[355px] md:h-[700px] xl:h-[624px] rounded-[18px] xl:rounded-[38px] bg-[#EAEEF9] mt-[25px] xl:mt-[35px] px-[45px] mx-[27px] xl:mr-[108px] xl:ml-[109px]  flex flex-col xl:flex-row justify-between">
        <div class="mt-[42px] md:mx-[100px] xl:mt-[155px] xl:mr-[85px]">
          <h1 class="font-vazir h-[31px] xl:h-[82px] font-black text-xl md:text-[30px] xl:text-[39px]">فناوری در دستان شما...</h1>
          <h3 class="font-vazir font-normal h-[71px] xl:h-[130px] max-w-[186px] md:max-w-[250px] xl:max-w-[386px] text-[11px] md:text-[16px] xl:text-2xl text-[#7B7575] leading-[17.19px] md:leading-[27px] xl:leading-[37.5px]">همایش هوش مصنوعی ۵روزه  با بهترین اساتید و کارگاه های مفید برای مهندس های کامپیوتر هر روز باید بروز شد با ما
          </h3>
          <div class="flex justify-between xl:justify-start items-center mx-[27px] md:mr-0 md:ml-[25px] xl:mx-0 md:mt-5 xl:mt-10">
            <a href="#" class="w-[68px] md:w-[95px] xl:w-[150px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center ml-6 xl:ml-4">
              <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">ثبت نام کنید </span>
            </a>
            <a href="#" class="w-[68px] md:w-[95px] xl:w-[150px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#FFBF26] rounded-[11px] xl:rounded-3xl flex items-center justify-center">
              <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">جزئیات بیشتر</span>
            </a>
          </div>
        </div>
        <div class=" w-full xl:w-[533px] h-full xl:h-[533px] flex xl:block justify-center">
          <img src="./../Pic/pic2.png" alt="فناوری" class=" w-[154px] xl:w-full md:w-[350px] h-[154px] xl:h-full md:h-[350px] mx-[31px] xl:mx-0 mt-6 xl:mt-[51px] mb-[40px] xl:pl-[52px]">
        </div>
      </div>
    </div>
    <!-- Task 2 -->
    <div class="flex w-full xl:mt-[74px]">
      <div class="w-full flex flex-col items-center xl:flex-row justify-between xl:mx-[174px]">
        <div class="item1 block">
          <div class="flex gap-x-8 md:gap-x-20 xl:gap-x-0 mb-4 xl:mb-[22px]">
            <img src="../Pic/pic1part3.png" alt="pic1" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
            <img src="../Pic/pic2 part 3.png" alt="pic2" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
            <img src="../Pic/pic3 part 3.png" alt="pic3" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
          </div>
          <div class="flex gap-x-8 md:gap-x-20  xl:gap-x-0">
            <img src="../Pic/pic4 part 3.png" alt="pic4" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
            <img src="../Pic/pic5 part 3.png" alt="pic5" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
            <img src="../Pic/pic6 part 3.png" alt="pic6" class="xl:w-[116px] md:w-[7rem] w-[61px] xl:h-[48px] md:h-20 h-[28px]">
          </div>
        </div>
        <div class="item2 my-[17px] xl:mt-0">
          <h1 class="font-vazir font-bold text-[10px] md:text-[22px] xl:text-[32px] leading-[17.19px] md:leading-[30px] xl:leading-[50px]">مورد اعتماد بیش از ۴۰،۰۰۰ کسب و کار آنلاین</h1>
          <h2 class="font-vazir font-normal text-[9px] md:text-[14px] xl:text-2xl leading-[15.63px] md:leading-[22px] xl:leading-[37.5px] max-w-[183px] md:max-w-[390px] xl:max-w-[595px]">
            بیش از ۴۰،۰۰۰ کسب و کار آنلاین ایرانی از استارتاپ ما استفاده کردن و ما با بهترین مشاور ها به آنها کمک کردیم....
          </h2>
        </div>
        </div>
    </div>
    <!-- Task 3 -->
     <div class="w-full h-auto xl:h-[2273px] bg-[#EAEEF9] mt-[74px] rounded-[18px] xl:rounded-[37px]">
      <div class="flex flex-col justify-center items-center">
        <!-- div1 -->
        <div class="flex flex-col md:flex-row md:gap-x-5 xl:gap-x-0">
          <div class="item1-2 mt-[12px] md:mt-[50px] xl:mt-[96px] mx-[20px] xl:mr-[251px] xl:ml-0">
            <h1 class="font-vazir font-bold text-[12px] md:text-[22px] xl:text-[32px] leading-[19px] md:leading-[35px] xl:leading-[50px]">زمان و مکان برگزاری همایش :</h1>
            <div class="mt-[8px] md:mt-[20px] xl:mt-[60px]">
              <span class="flex justify-start items-center text-[10px] md:text-[15px] xl:text-xl font-vazir font-medium md:font-normal leading-[16px] xl:leading-[32px] gap-x-1 xl:gap-x-[19px] mb-[11px] xl:mb-[20px]">
                <svg class="xl:w-8 md:w-6 w-4 xl:h-8 md:h-6 h-4">
                  <use href="#Date" ></use>
                </svg>
                تاریخ :۱شهریور تا ۵شهریور 
              </span>
              <span class="flex justify-start items-center text-[10px] md:text-[15px] xl:text-xl font-vazir font-medium md:font-normal leading-[16px] xl:leading-[32px] gap-x-1 xl:gap-x-[19px] mb-[11px] xl:mb-[20px]">
                <svg class="xl:w-8 w-4 xl:h-8 h-4">
                  <use href="#Location" ></use>
                </svg>
                مکان :دانشگاه ایلام 
              </span>
              <span class="flex justify-start items-center text-[10px] md:text-[15px] xl:text-xl font-vazir font-medium md:font-normal leading-[16px] xl:leading-[32px] gap-x-1 xl:gap-x-[19px] mb-[11px] xl:mb-[20px]">
                <svg class="xl:w-8 w-4 xl:h-8 h-4">
                  <use href="#Time" ></use>
                </svg>
                ساعت: ۹صبح 
                </span>
            </div>
              <a href="#" class="w-[68px] md:w-[95px] xl:w-[150px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center ml-6 xl:ml-4">
                <span class="font-vazir font-black md:font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">ثبت نام کنید </span>
              </a>
          </div>
          <div class="item2-2 m-0 xl:mr-[163px] md:mt-[30px] xl:mt-[23px]">
            <img src="../Pic/PicOfTask3/Layer 1.png" alt="img1" class="xl:w-[527px] md:w-[350px] w-[168px] xl:h-[407px] md:h-[250px] h-[105px]">
          </div>
        </div>
        <!-- div2 -->
        <div class="mt-[17px] md:mt-[100px] xl:mt-[181px]">
          <div class="flex flex-col md:flex-row mx-[25px] md:mx-0">
            <div class="xl:mr-[135px]">
              <img src="../Pic/PicOfTask3/Layer 2.png" alt="img2" class="xl:w-[487px] md:w-[320px] w-[168px] xl:h-[397px] md:h-[270px] h-[112px]">
            </div>
            <div class="flex flex-col justify-center xl:items-start xl:justify-normal items-center mx-[21px] xl:mr-[192px] mt-[27px] xl:mt-[61px]">
              <p class="font-vazir font-bold text-[12px] md:text-[22px] xl:text-[32px] leading-[19px] md:leading-[35px] xl:leading-[50px] mb-[3px] xl:mb-[9px]">همه نظرات را ببینید و پاسخگو باشید</p>
              <h1 class="font-vazir font-bold text-[11px] md:text-[17px] xl:text-2xl mb-[7px] md:mb-[9px]">نظرات دانش آموخته ها در سال های قبل</h1>
              <p class="font-vazir font-normal text-[10px] md:text-[15px] xl:text-xl max-w-[151px] md:max-w-[220px] xl:max-w-[296px] leading-[16px] xl:leading-[31.25px] mb-[9px]">صرفه‌جویی در زمان با مشاهده همه کامنت‌ها در یک صفحه و افزایش تعامل از طریق پاسخگویی سریع به کامنت‌ها در شبکه‌های اجتماعی</p>
              <div class="w-full xl:w-auto mr-[21px] md:mr-[88px] xl:mr-0 mt-[12px] xl:mt-[30px]">
                <a href="#" class="mb-[30px] w-[68px] md:w-[110px] xl:w-[176px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center">
                <span class="font-vazir font-normal text-[8px] md:text-[15px] xl:text-xl text-white">کامنت هارا بیینید</span>
              </a>
              </div>
            </div>
          </div>
        </div>
        <!-- div3 -->
        <div class="h-auto xl:h-[530px]">
          <div class="w-full flex flex-col md:flex-row xl:mr-[180px]">
            <div class="item1-3 mt-[22px] md:mt-[190px] xl:mt-[304px]">
              <h1 class=" md:max-w-[315px] font-vazir font-bold text-[12px] md:text-[22px] xl:text-[32px] leading-[19px] md:leading-[35px] xl:leading-[50px] mb-[7px] xl:mb-0"> همایش هوش مصنوعی: آینده‌نگری در دنیای دیجیتال </h1>
              <p class="max-w-[176px] md:max-w-[240px] xl:max-w-[423px] font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl leading-[16px] md:leading-[22px] xl:leading-[38px] mr-[15px] md:mr-0">به جمع پیشگامان دنیای فناوری بپیوندید و در [همایش آیندگان ] شاهد تحولاتی شگرف در عرصه هوش مصنوعی باشید!</p>
                <a href="#" class="mt-[14px] md:mt-[28px] xl:mt-[40px] w-[68px] md:w-[95px] xl:w-[176px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center mr-[15px] md:mr-0">
                <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-xl text-white">شروع کنید </span>
              </a>
            </div>
            <div class="item2-3 mt-[20px] md:mt-[140px] xl:mt-[166px] mx-[33px] xl:mr-[41px]">
              <img src="../Pic/PicOfTask3/ai 1.png" alt="img3" class="xl:w-[558px] md:w-[350px] w-[154px] xl:h-[528px] md:h-[320px] h-[122px] ">
            </div>
          </div>
        </div>
        <!-- div4 -->
        <div>
          <div class="pb-[35px] md:pb-[70px] xl:pb-[105px] flex flex-col md:flex-row">
            <div class="mt-[15px] md:mt-[70px] xl:mt-[186px] xl:mr-[141px]">
              <img src="../Pic/PicOfTask3/analytics (1) 1.png" alt="img4" class="xl:w-[467px] md:w-[310px] w-[168px] xl:h-[395px] md:h-[270px] h-[130px]">
            </div>
            <div class="xl:mr-[129px] mt-[33px] md:mt-[120px] xl:mt-[236px] w-auto xl:max-w-[430px]">
              <h1 class="font-vazir text-[12px] md:text-[20px] xl:text-[28px] font-black leading-[19px] md:leading-[30px] xl:leading-[48px]">بازدیدشرکت های مرتبط و تحلیل دادها </h1>
              <p class="font-vazir font-normal text-[10px] md:text-[16px] xl:text-lg leading-[16px] md:leading-[22px] xl:leading-[28px] max-w-[162px] md:max-w-[270px] xl:max-w-[345px] mr-[14px] xl:mr-0">
                به بازدید از مجموعه‌های صنعتی و استارتاپ‌های موفق خواهند پرداخت. این بازدیدها فرصتی برای مشاهده عملی نحوه عملکرد استارتاپ‌ها و تبادل نظر با بنیان‌گذاران و تیم‌های اجرایی آن‌ها فراهم خواهد کرد.
              </p>
              <a href="#" class="mt-[15px] xl:mt-[40px] w-[68px] md:w-[95px] xl:w-[156px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center mr-[14px] xl:mr-0">
                <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">شروع کنید </span>
              </a>
            </div>
          </div>
        </div>
      </div>
     </div>
     <!-- Task 4 -->
      <div class="mt-[20px] mb-[20px] md:mb-[50px] xl:mb-[110px] flex justify-center xl:w-full mx-[10px] xl:mx-0 xl:h-[758px]">
        <img src="../Pic/videoOfLandingPage/a9d485288741ba6752e1e177a3757919.jfif" alt="img5" class="xl:w-full w-[90vw] xl:h-[758px] md:h-[350px] h-[186px] rounded-[16px] xl:rounded-none object-cover">
      </div>
      <!-- Task 5 -->
       <div class="w-full flex flex-col xl:flex-row ml-[234px] justify-between items-center mr-[14px]">
        <div>
          <h1 class="w-full font-vazir items-center font-bold text-[12px] md:text-[17px] xl:text-2xl leading-[15px] md:leading-[30px] xl:leading-[38px]">هوش مصنوعی رایچت برای تمامی سیستم عامل ها</h1>
        </div>
        <div class="flex gap-x-[11px] md:gap-x-[20px] xl:gap-x-[44px] ml-0 xl:ml-[234px] items-center">
          <svg class="w-[31px] xl:w-10 h-[28px] xl:h-[37px]">
            <use href="#World">
            </use>
          </svg>
          <svg class="w-[40px] xl:w-[49px] h-[35px] xl:h-[44px]">
            <use href="#Android">
            </use>
          </svg>
          <div class="flex flex-col rounded-[18px] justify-between items-center w-[48px] xl:w-[90px] h-[63px] xl:h-[112px] bg-[#D9D9D9]">
            <svg class="w-[35px] xl:w-[54px] h-[30px] xl:h-[44px]">
              <use href="#Ios">
              </use>
            </svg>
            <span class="font-vazir font-bold text-[10px] xl:text-[20px] mb-4">
              macOs
            </span>
          </div>
          <svg class="w-[35px] xl:w-[54px] h-[30px] xl:h-[44px]">
            <use href="#Ios">
            </use>
          </svg>
          <svg class="w-[30px] xl:w-[54px] h-[35px] xl:h-[44px]">
            <use href="#Window">
            </use>
          </svg>
        </div>
       </div>
       <!-- Task 6 -->

        <div class="w-full h-[443px] xl:h-[636px] bg-[#EAEEF9] mt-5 xl:mt-[30px] rounded-[60px]">
          <v-carousel style="height: 100%; border-radius: 60px;" hide-delimiter-background :show-arrows="false" cycle :interval="5000" >
    <v-carousel-item v-for="(slide, i) in chunkedSlides" :key="i" class="flex justify-center">
      <v-sheet height="100%">
        <v-container class="fill-height d-flex justify-center align-center bg-[#EAEEF9] overflow-hidden px-5">
          <v-row>
            <v-col v-for="(item, j) in slide" :key="j" cols="3" class="h-auto mb-2">
              <v-sheet class="d-flex flex-column items-center w-[220px] xl:w-[266px] h-full" style="border-radius: 34px;">
                <img :src="item.image" alt="Image" class="w-[168px] xl:w-[228px] h-[148px] xl:h-[185px] mt-5 mb-2" />
                <span dir="rtl" class="font-vazir font-normal text-[13px] xl:text-base px-[11px] mt-[23px] pb-[30px]">{{ item.text }}</span>
              </v-sheet>
            </v-col>
          </v-row>
        </v-container>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
        </div>
        <!-- Task 7 -->
         <div class="mt-[60px] w-full flex justify-center items-center">
          <div class="w-[293px] md:w-[700px] xl:w-[1138px] border-[1px] border-solid border-black rounded-[33px] xl:rounded-[69px]">
            <div class="w-full flex flex-col justify-center items-center my-[10px] md:my-[35px] xl:my-[60px]">
              <span class="font-vazir font-bold text-[10px] md:text-xl xl:text-[32px] leading-[15px] md:leading-[30px] xl:leading-[50px] mb-[10px] xl:mb-[26px]">اولین همایش ۵ روزه هوش مصنوعی در ایلام </span>
              <span class="font-vazir font-normal text-[10px] md:text-xl xl:text-[32px] leading-[15px] md:leading-[30px] xl:leading-[50px] mb-[15px] md:mb-[30px] xl:mb-[52px]">با ما اولین هارو تجربه کنید </span>
              <div class="flex">
                <a href="#" class="w-[68px] md:w-[95px] xl:w-[150px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#06AFEA] rounded-[11px] xl:rounded-3xl flex items-center justify-center ml-6 xl:ml-4">
              <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">ثبت نام کنید </span>
            </a>
            <a href="#" class="w-[68px] md:w-[95px] xl:w-[150px] h-[26px] md:h-[38px] xl:h-[56px] bg-[#FFBF26] rounded-[11px] xl:rounded-3xl flex items-center justify-center">
              <span class="font-vazir font-normal text-[10px] md:text-[17px] xl:text-2xl text-white">جزئیات بیشتر</span>
            </a>
              </div>
            </div>
          </div>
         </div>
         <!-- Task 8 -->
          <div>
            <span class="w-full flex justify-center items-center font-vazir font-black text-[10px] md:text-[17px] xl:text-[32px] leading-[15px] md:leading-[30px] xl:leading-[50px] mt-[29px]">آنچه دیگران می‌گویند...</span>
            <div class="w-full flex justify-center items-center">
              <img src="../Pic/9dd5e54815429785e7a370d64972a5c7.png" alt="img7" class="w-[55px] md:w-[75px] xl:w-[120px] h-[60px] md:h-[80px] xl:h-[130px]">
            </div>
            <div class="w-full flex justify-center items-center mt-8 h-[100px]">
              <span v-if="ishoveredClassSpan === 1" class="font-vazir text-xs md:text-[15px] xl:text-[20px] leading-[18px] md:leading-[25px] xl:leading-[31px] max-w-[225px] md:max-w-[450px] xl:max-w-[876px] text-center">عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .
              </span>
              <span v-if="ishoveredClassSpan === 2" class="font-vazir text-xs md:text-[15px] xl:text-[20px] leading-[18px] md:leading-[25px] xl:leading-[31px] max-w-[225px] md:max-w-[450px] xl:max-w-[876px] text-center">عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .
              </span>
              <span v-if="ishoveredClassSpan === 3" class="font-vazir text-xs md:text-[15px] xl:text-[20px] leading-[18px] md:leading-[25px] xl:leading-[31px] max-w-[225px] md:max-w-[450px] xl:max-w-[876px] text-center">اگر اولویت کسب وکار شما ارائه خدمات با کیفیت به مشتریان‌تون با هدف بالا بردن فروش و پاسخگویی در کمترین زمان هست به نظر من رایچت بهترین گزینه برای شما خواهد بود.</span>
            </div>
            <div class="mt-20 w-full flex flex-col md:flex-row justify-center items-center gap-y-[5px] md:gap-x-[25px]">
              <div @mouseenter="ishovered(1)" :class="{'hovered' : ishoveredClass === 1 }" class="w-[222px] md:w-[270px] xl:w-[371px] h-[61px] md:h-[90px] xl:h-[138px] rounded-[13px] xl:rounded-[28px] bg-[#E3EAF2] flex items-center justify-between">
                <div class="w-[49px] md:w-[70px] xl:w-[124px] mr-[13px]"><img src="../Pic/dehban.png" alt="img8" class="rounded-[50%]">
                </div>
                <div class="flex flex-col ml-[2px] md:ml-[5px] xl:ml-[13px] mr-[2px] md:mr-[5px] xl:mr-[9px]">
                  <span class="font-vazir font-bold text-[10px] md:text-[18px] leading-[15px] md:leading-[31px]">مهدی دهبان</span>
                  <span class="font-vazir font-normal text-[10px] md:text-[18px] leading-[15px] md:leading-[31px]">دکترای بازایابی و موسس آکادمی دهبان</span>
                </div>
              </div>
              <div @mouseenter="ishovered(2)" :class="{'hovered' : ishoveredClass === 2 }"  class="w-[222px] md:w-[270px] xl:w-[371px] h-[61px] md:h-[90px] xl:h-[138px] rounded-[13px] xl:rounded-[28px] bg-[#E3EAF2] flex items-center justify-between">
                <div class="w-[49px] md:w-[70px] xl:w-[124px] mr-[13px]"><img src="../Pic/talebi.png" alt="img8" class="rounded-[50%]">
                </div>
                <div class="flex flex-col ml-[2px] md:ml-[5px] xl:ml-[13px] mr-[2px] md:mr-[5px] xl:mr-[9px]">
                  <span class="font-vazir font-bold text-[10px] md:text-[18px] leading-[15px] md:leading-[31px]">عادل طالبی</span>
                  <span class="font-vazir font-normal text-[10px] md:text-[18px] leading-[15px] md:leading-[31px]">استراتژیست کسب و کار های آنلاین 
                  </span>
                </div>
              </div>
              <div @mouseenter="ishovered(3)" :class="{'hovered' : ishoveredClass === 3 }"  class="w-[222px] md:w-[270px] xl:w-[371px] h-[61px] md:h-[90px] xl:h-[138px] rounded-[13px] xl:rounded-[28px] bg-[#E3EAF2] flex items-center justify-between">
                <div class="w-[49px] md:w-[70px] xl:w-[124px] mr-[13px]"><img src="../Pic/moz.png" alt="img8" class="rounded-[50%]">
                </div>
                <div class="flex flex-col items-center ml-[2px] md:ml-[5px] xl:ml-[13px] mr-[2px] md:mr-[5px] xl:mr-[9px]">
                  <span class="font-vazir font-bold md:text-[18px]  text-[10px] md:leading-[31px] leading-[15px] ml-[90px] md:ml-[124px]">آرین افشار</span>
                  <span class="font-vazir font-bold md:text-[18px] text-[10px] md:leading-[31px] leading-[15px]">مدیر جوانه</span>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full">
            <span class="mt-[80px] font-vazir font-black text-[16px] md:text-[25px] xl:text-4xl leading-[25px] xl:leading-[56px] flex justify-center items-center mb-[10px] md:mb-5">مهمان‌های ویژه </span>
            <div class="flex flex-col md:flex-row justify-center items-center gap-y-[10px] md:gap-x-[30px] xl:gap-x-[60px]">
              <div class="w-[220px] xl:w-[315px] h-[364px] xl:h-[535px] bg-[#D9D9D95E] rounded-[44px] flex flex-col items-center">
                <div><img src="../Pic/rexa.jpg" alt="img9" class="w-[168px] xl:w-[272px] h-[148px] xl:h-[243px] rounded-[29px] xl:rounded-[39px] mt-[23px]"></div>
                <div class="flex flex-col items-center max-w-[281px] mt-[14px] xl:mt-[10px] gap-y-2">
                  <span class="font-vazir font-black text-[12px] md:text-[16px] xl:text-xl leading-[19px] xl:leading-[32px] ">مهندس محمد رضا اقایی </span>
                  <span class="font-vazir font-black text-xs xl:text-lg leading-[18px] xl:leading-[28px]">بنیان گذار   استارتاپ     با سلام </span>
                  <span class="font-vazir font-normal pr-[8px] md:pr-0  text-xs xl:text-lg leading-[18px] xl:leading-[28px]">محمدرضا مهندس شبکه‌ بوده، بعدش فلسفه هنر خونده، ولی آدم درس خوندن نیست. بیشتر به ساختن و توسعه دادن علاقه داره. اولین عضو باسلامه و مسئله اولش شکوفایی آدم‌ها بوده</span>
                </div>
              </div>
              <div class="w-[220px] xl:w-[315px] h-[364px] xl:h-[535px] bg-[#D9D9D95E] rounded-[44px] flex flex-col items-center">
                <div><img src="../Pic/aghaee.jpg" alt="img9" class="w-[168px] xl:w-[272px] h-[148px] xl:h-[243px] rounded-[29px] xl:rounded-[39px] mt-[23px]"></div>
                <div class="flex flex-col items-center max-w-[281px] mt-[14px] xl:mt-[10px] gap-y-2">
                  <span class="font-vazir font-black text-[12px] md:text-[16px] xl:text-xl leading-[19px] xl:leading-[32px] ">مهندس احمد واشقانی </span>
                  <span class="font-vazir font-black text-xs xl:text-lg leading-[18px] xl:leading-[28px]">مدیر ارشد و سرمایه گذار تیم دیجیکالا </span>
                  <span class="font-vazir font-normal pr-[8px] md:pr-0  text-xs xl:text-lg leading-[18px] xl:leading-[28px]"> دانشگاه مگ گیل کانادا هستند. ایشان از مهرماه 1369 پس از گرفتن مدرک دکتری همکاری خود را با دانشگاه تربیت مدرس آغاز کرده و افزون بر فعالیت‌های آموزشی و پژوهشی، دارای</span>
                </div>
              </div>
              <div class="w-[220px] xl:w-[315px] h-[364px] xl:h-[535px] bg-[#D9D9D95E] rounded-[44px] flex flex-col items-center">
                <div><img src="../Pic/talebi2.png" alt="img9" class="w-[168px] xl:w-[272px] h-[148px] xl:h-[243px] rounded-[29px] xl:rounded-[39px] mt-[23px]"></div>
                <div class="flex flex-col items-center max-w-[281px] mt-[14px] xl:mt-[10px] gap-y-2">
                  <span class="font-vazir font-black text-[12px] md:text-[16px] xl:text-xl leading-[19px] xl:leading-[32px] ">عادل طالبی</span>
                  <span class="font-vazir font-black text-xs xl:text-lg leading-[18px] xl:leading-[28px]">استراتژیست کسب و کار های آنلاین</span>
                  <span class="font-vazir font-normal pr-[8px] md:pr-0  text-xs xl:text-lg leading-[18px] xl:leading-[28px]"> دانشگاه مگ گیل کانادا هستند. ایشان از مهرماه 1369 پس از گرفتن مدرک دکتری همکاری خود را با دانشگاه تربیت مدرس آغاز کرده و افزون بر فعالیت‌های آموزشی و پژوهشی، دارای</span>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full flex justify-center my-[70px]">
            <div class="w-[90%] border-2 border-solid border-black">
            </div>
          </div>
          <!-- Task 9 -->
           <div class="w-full flex flex-wrap justify-center items-center gap-x-[14px] md:gap-x-[30px] xl:gap-x-[60px]" >
            <img src="../Pic/l1.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
            <img src="../Pic/l2.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
            <img src="../Pic/l3.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
            <img src="../Pic/l4.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
            <img src="../Pic/l5.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
            <img src="../Pic/l6.png" alt="img" class="xl:w-[105px] mb-[14px] md:mb-0 w-[80px] xl:h-[105px] h-[80px]">
           </div>
    </main>
    <footer class="pt-9 pb-16 gap-x-[150px] w-full rounded-t-[62px] h-[510px] flex flex-col md:flex-row justify-center bg-[#EAEEF9] mt-[110px]">
        <div class="flex flex-col items-center justify-center gap-y-[5px] md:gap-y-5">
          <img src="../Pic/5f2ec6d494f394978131ba14a690d793.png" alt="img" class="xl:w-[100px] w-[60px] xl:h-[100px] h-[60px]">
          <span class="font-vazir font-bold text-[14px] md:text-[22px] xl:text-2xl leading-[21px] xl:leading-[37px]">راه‌های ارتباطی</span>
          <div class="flex gap-x-[4px] xl:gap-x-[11px] mt-1 xl:mt-5">
          <div class="w-[34px] xl:w-[52px] h-[34px] xl:h-[52px] bg-white flex justify-center items-center rounded-[10px]">
            <svg class="w-5 xl:w-[34px] h-5 xl:h-[34px]">
              <use href="#Twi"></use>
            </svg>
          </div>
          <div class="w-[34px] xl:w-[52px] h-[34px] xl:h-[52px] bg-white flex justify-center items-center rounded-[10px]">
            <svg class="w-5 xl:w-[34px] h-5 xl:h-[34px]">
              <use href="#In"></use>
            </svg>
          </div>
          <div class="w-[34px] xl:w-[52px] h-[34px] xl:h-[52px] bg-white flex justify-center items-center rounded-[10px]">
            <svg class="w-5 xl:w-[34px] h-5 xl:h-[34px]">
              <use href="#Insta"></use>
            </svg>
          </div>
          <div class="w-[34px] xl:w-[52px] h-[34px] xl:h-[52px] bg-white flex justify-center items-center rounded-[10px]">
            <svg class="w-5 xl:w-[34px] h-5 xl:h-[34px]">
              <use href="#F"></use>
            </svg>
          </div>
          </div>
          <span class="font-vazir font-bold text-[14px] md:text-[22px] xl:text-2xl leading-[21px] xl:leading-[38px] mt-[12px] xl:mt-[24px]">۰۹۹۱۸۷۲۰۳۴۴</span>
          <div class="flex gap-x-[7px] xl:gap-x-[30px]">
            <img src="../Pic/namad1.png" alt="img" class="xl:w-[101px] w-[50px] h-[50px] xl:h-[101px]">
            <img src="../pic/namad2.png" alt="img" class="xl:w-[107px] w-[50px] h-[50px] xl:h-[107px]">
          </div>
        </div>
        <div class="flex gap-x-[15px] md:gap-x-[150px] w-full md:w-auto justify-center md:justify-normal items-center mt-[20px] md:mt-0">
        <div class="flex flex-col items-start justify-center gap-y-[2px] xl:gap-y-[5px]" >
          <span class="font-vazir font-bold text-[12px] md:text-[20px] xl:text-2xl leading-[19px] xl:leading-[38px]">لینک های آیندگان </span>
          <a href="#" class="font-vazir font-normal xl:pr-[8px] text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">پنل مدیریت
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">اپ گفتگوی تحت وب
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">اتصال به واتس‌اپ
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">وضعیت سرویس ها
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">به‌روز رسانی ها
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">ثبت شکایات
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">امنیت رایچت
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">مستندات
          </a>

        </div>
        <div class="flex flex-col items-start justify-center gap-y-[5px]">
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">تماس با ما
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">درباره ما
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">مشتریان
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">شرایط استفاده
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">پشتیبانی جوابگو
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">فرصت های شغلی
          </a>
          <a href="#" class="font-vazir font-normal text-[11px] xl:text-2xl leading-[18px] xl:leading-[38px]">پیشنهاد شما چیه؟
          </a>

        </div>
      </div>
    </footer>
  </div>
</div>
</template>
<script setup>
import { ref , computed  } from 'vue';
const ishoveredClass = ref(null)
const ishoveredClassSpan = ref(1)
const items = [
  { image: new URL('@/Pic/imgOfSlider/1.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/2.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/3.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/4.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/1.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/2.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/3.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/4.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/1.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' },
  { image: new URL('@/Pic/imgOfSlider/2.jpg' , import.meta.url), text: 'عکاسی همایش ها، نشست ها و جلسات یکی از مهم ترین بخش های برگزاری چنین رویدادهاییست و نیاز به عکاسانی باهوش و خلاق دارند که بتوانند به بهترین شکل ممکن ثبت لحظات را انجام دهند. عکاسان کاربلد ما در پیکسمر نیز با دارا بودن .' }
];
const chunkedSlides = ref([]);
const itemsPerSlide = computed(() => {
  if (window.innerWidth < 500) {
    return 1;
  } else if (window.innerWidth < 780) {
    return 2;
  } else if (window.innerWidth < 950){
    return 3;
  }
  else {
    return 4;
  }
});
for (let i = 0; i < items.length; i += itemsPerSlide.value) {
  chunkedSlides.value.push(items.slice(i, i + itemsPerSlide.value));
}
const ishovered = (index) => {
  ishoveredClass.value = index
  ishoveredClassSpan.value = index
}
const divOfHeaderMb = ref(false)
const opendivOfHeaderMb = () => {
  divOfHeaderMb.value = !divOfHeaderMb.value
}
</script>
<style>
.hovered {
  background-color: #B5D4F7;
}
.nothovered {
  background-color: #E3EAF2;
}
.v-col-3 {
  max-width: none;
}
@media (min-width:300px) {
.v-btn--icon.v-btn--density-default {
    width : 25px ;
    height : 25px;
    /* display : flex ; 
    justify-content : center ; */
}
}
.v-carousel__controls {
  display: flex !important;

}
.v-carousel__controls__item {
  background-color: #D9D9D9;
}
.v-carousel__controls__item--active {
  background-color: #5A5555;
}
.v-btn--active {
  background-color: #5A5555 !important;
}

.v-responsive__content {
    justify-content: center;
    display: flex;
    flex: 1 0 0px;
    max-width: 100%; 
}
.v-container {
  max-width: unset;
  width: 100%;
}
@media (min-width:300px) {
  .item1 {
  order: 2;
}
.item2 {
  order: 1;
}
}

@media (min-width:1280px) {
  .item1 {
  order: 1;
}
.item2 {
  order: 2;
}
}
@media (min-width:300px) {
  .item1-2 {
  order: 2;
}
.item2-2 {
  order: 1;
}
}
@media (min-width:1280px) {
  .item1-2 {
  order: 1;
}
.item2-2 {
  order: 2;
}
}
@media (min-width:300px) {
  .item1-3 {
  order: 2;
}
.item2-3 {
  order: 1;
}
}
@media (min-width:1280px) {
  .item1-3 {
  order: 1;
}
.item2-3 {
  order: 2;
}
}

@media (min-width:300px) {
  .mainshodow {
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
  }
}
@media (min-width:768px) {
  .mainshodow {
box-shadow: 2px 2px 4px 2px rgba(0, 0, 0, 0.25);

}
}
@media (min-width:768px) {
  li span.textSpan {
  font-weight: 800;
  font-size: 13px;
  color: rgba(90, 85, 85, 1);
  line-height: 20px;
}
}
@media (min-width:1024px) {
  li span.textSpan {
  font-weight: 800;
  font-size: 17px;
  color: rgba(90, 85, 85, 1);
  line-height: 20px;
}
}
@media (min-width:1280px) {
  li span.textSpan {
  font-weight: 900;
  font-size: 20px;
  color: rgba(90, 85, 85, 1);
  line-height: 32px;
}
}

@media (min-width:300px) {
  li span.textSpan2 {
  font-weight: 900;
  font-size: 20px;
  color: black;
  line-height: 31.25px;
}
}

input {
  outline: none;
  border: 1px solid rgba(255, 191, 38, 1);
}
.customPlace::placeholder {
  padding: 8px 0px 7px 63px;
  font-size: 20px;
  font-weight: 700;
  font-family: 'Vazirmatn';
}
.btnOfHeader {
  background-color:rgba(6, 175, 234, 1);
}
.spanOfHeader {
  color: rgba(255, 255, 255, 1);
}
.btnOfHeaderMb {
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);

}
</style>