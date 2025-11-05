<script setup></script>
<template>
    <div class="w-screen h-screen bg-cyan-700 flex flex-col justify-center items-center">
        <div class="p-5 text-white text-2xl">
            Welcome Back to H!App!!!
        </div>
        <div class="bg-cyan-300 w-fit p-7 rounded-2xl">
            <form action="" @submit.prevent="" class="h-fit w-fit flex flex-col justify-center items-center gap-4">
                <div class="flex flex-col">
                    <label for="email">Email</label>
                    <input type="email" name="email" id="" class="bg-white p-1 rounded-md" required>
                </div>
                <div class="flex flex-col">
                    <label for="password">Password</label>
                    <input type="password" name="" id="" class="bg-white p-1 rounded-md" required>
                </div>
                <div class="flex gap-4">
                    <button type="submit" class="p-2 bg-cyan-700 text-white rounded-md">
                        Login
                    </button>
                    <NuxtLink to="/register" class="p-2 bg-cyan-500 text-white rounded-md">
                        Register
                    </NuxtLink>
                </div>
            </form>
        </div>
    </div>
</template>