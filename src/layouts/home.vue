<template>
  <div class="px-4 py-10 text-center text-gray-700 dark:text-gray-200">
    <el-container>
      <el-aside width="200px" class="bg-blue-500">
        Aside
      </el-aside>
      <el-container>
        <el-header class="bg-green-500">
          Header
        </el-header>
        <el-main class="bg-orange-500">
          <RouterView />
        </el-main>
        <el-footer class="bg-pink-500">
          <div class="mt-5 mx-auto text-center opacity-25 text-sm">
            [Home Layout]
          </div>
          <Footer />
        </el-footer>
      </el-container>
    </el-container>
  </div>
</template>
