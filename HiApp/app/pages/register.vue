<script setup></script>
<template>
    <div class="w-screen h-screen bg-cyan-700 flex flex-col items-center">
        <div class="flex flex-col items-center p-5 text-white text-lg">
            <p class="text-white text-2xl">Welcome to H!App!!!</p>
            <p>Communicate with ease</p>
        </div>
        <div class="bg-cyan-300 w-fit p-7 rounded-2xl">
            <form action="" @submit.prevent="" class="h-fit w-fit flex flex-col justify-center items-center gap-4">
                <div class="grid grid-cols-2 gap-4">
                    <div class="flex flex-col">
                        <label for="lastname">Last Name<span class="text-red-500">*</span></label>
                        <input type="text" name="lastname" id="" class="bg-white p-1 rounded-md" required>
                    </div>
                    <div class="flex flex-col">
                        <label for="firstname">First Name<span class="text-red-500">*</span></label>
                        <input type="text" name="firstname" id="" class="bg-white p-1 rounded-md" required>
                    </div>
                    <div class="flex flex-col col-span-2">
                        <label for="othername">Other Name</label>
                        <input type="text" name="othername" id="" class="bg-white p-1 rounded-md">
                    </div>
                </div>
                <div class="flex flex-col">
                    <label for="email">Email<span class="text-red-500">*</span></label>
                    <input type="email" name="email" id="" class="bg-white p-1 rounded-md" required>
                </div>
                <div class="flex flex-col">
                    <label for="dob">Date of Birth<span class="text-red-500">*</span></label>
                    <input type="date" name="dob" id="" class="bg-white p-1 rounded-md" required>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <div class="flex flex-col">
                        <label for="password">Password<span class="text-red-500">*</span></label>
                        <input type="password" name="password" id="" class="bg-white p-1 rounded-md" required>
                    </div>
                    <div class="flex flex-col">
                        <label for="conpassword">Confirm Password</label>
                        <input type="password" name="conpassword" id="" class="bg-white p-1 rounded-md">
                    </div>
                </div>
                <div class="flex gap-4">
                    <button type="submit" class="p-2 bg-cyan-700 text-white rounded-md">
                        Register
                    </button>
                    <NuxtLink to="/login" class="p-2 bg-cyan-500 text-white rounded-md">
                        Login
                    </NuxtLink>
                </div>
            </form>
        </div>
    </div>
</template>