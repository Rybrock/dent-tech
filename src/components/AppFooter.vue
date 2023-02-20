<template>
  <div class="app-footer p-4 border-t border-white">
    <div class="mt-10 md:mt-5">
      <nav
        class="
          text-white
          flex 
          flex-col
          md:flex-row
          justify-between
          text-xl
          font-semibold
          space-x-0
          space-y-5
          md:space-y-0
          md:space-x-2
        "
      >
        <div class="flex flex-col justify-center items-center">
          <p class="text-xs">Find us on Facebook</p>
          <a href="https://www.facebook.com/profile.php?id=100087966960493" target="_blank">
            <img src="../assets/icons8-facebook.svg" alt="" />
          </a>
        </div>

        <div class="flex flex-col justify-center items-center">
          <p class="text-xs">copyright © Dent-Tech 2023</p>
        </div>

        <div class="flex flex-col justify-center items-center space-x-0 md:space-x-4">
          <div class="flex flex-col md:flex-row justify-center space-x-0 md:space-x-2 items-center space-y-2 md:space-y-0">
            <div>
              <img
                src="../assets/molumen_phone_icon.svg"
                width="20"
                height="20"
                alt=""
              />
            </div>
            <div>
              <a href="Tel:07907 182801">
                <p class="text-white text-xs">07907 182801</p>
              </a>
            </div>
          </div>

          <div class="flex flex-col md:flex-row justify-center items-center space-x-0 md:space-x-2 space-y-2 md:space-y-0">
            <div>
              <img src="../assets/mail-142.svg" width="20" height="20" alt="" />
            </div>
            <div>
              <a href="mailto:07907 182801">
                <p class="text-white text-xs">dent-tech22@outlook.com</p>
              </a>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>
  
  <script>
export default {
  data() {
    return {};
  },
};
</script>
  
  <style scoped>
.app-footer {
  background-color: #221b1b;
}
</style>
  