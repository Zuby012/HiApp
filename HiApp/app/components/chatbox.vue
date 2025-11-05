<script setup>

function scrollToBottom() {
    const chatBox = document.getElementById('chatbox');
    chatBox.scrollTop = chatBox.scrollHeight
}

</script>
<template>
        <div class="w-full h-screen bg-cyan-500">
            <div class="relative w-full h-135 shadow-2xl p-5 flex flex-col justify-between overflow-y-auto">
                <div class="fixed w-215 p-3 rounded-lg bg-cyan-900 text-white flex justify-between items-center">
                    <span>User name</span><span>options</span>
                </div>
                <div id="chatbox" class="h-full w-full flex flex-col gap-4 pt-15 pb-20 mb-10">
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hi
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                    <div class="bg-black text-white p-3 w-fit h-fit rounded-lg">
                        hello
                    </div>
                </div>
            </div>
            <div class="h-fit w-full p-3 flex items-center">
                <form action="" class="w-full flex justify-center gap-4">
                    <input type="text" placeholder="Message" class="w-full p-3 rounded-lg bg-gray-700 text-white">
                    <button class="p-3 rounded-lg bg-cyan-900 text-white">Send</button>
                </form>
            </div>
        </div>
</template>