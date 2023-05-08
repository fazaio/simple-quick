<template>
    <section>
        <div class="flex p-3 border-b-2 items-center">
            <div class="flex-none w-10">a</div>
            <div class="flex-grow">
                <p class="text-blue-400 font-bold">109220-Naturization</p>
                <p class="text-gray-500 text-xs">3 Participant</p>
            </div>
            <div class="flex-none w-10 text-right mr-2">X</div>
        </div>
        <div class="px-3 py-2 overflow-auto">
            <div class="grid">
                <div class="text-right text-xs justify-self-end w-2/3">
                    <p class=" text-gray-500">You</p>
                    <div class="flex">
                        <div class="mr-2">...</div>
                        <div class="p-3 rounded bg-purple-200 text-gray-600 text-left">
                            <p>
                                Itaque pariatur cumque atque ipsum ut, mollitia ducimus corrupti fugit quia, officia
                                aspernatur
                                sit
                                esse fugiat! Officia, rem excepturi.
                            </p>
                            <p class="mt-1">19:32</p>
                        </div>
                    </div>
                </div>
                <div class="text-left mt-2 text-xs justify-self-start w-2/3">
                    <p class=" text-orange-400 font-bold">Marr Hilda</p>
                    <div class="flex">
                        <div class="p-3 rounded bg-orange-100 text-gray-600 text-left">
                            <p>
                                Itaque pariatur cumque atque ipsum ut, mollitia ducimus corrupti fugit quia, officia
                                aspernatur
                                sit
                                esse fugiat! Officia, rem excepturi.
                            </p>
                            <p class="mt-1">19:32</p>
                        </div>
                        <div class="ml-2">...</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="absolute bottom-0 p-3 w-full">
            <div class="flex items-center">
                <div class="flex-grow mr-2">
                    <input type="text" class="rounded outline-none border-2 py-2 px-3 w-full"
                        placeholder="Type a new message">
                </div>
                <div class="flex-none">
                    <button class="rounded py-2 px-3 bg-blue-500 text-white">Send</button>
                </div>
            </div>
        </div>
    </section>
</template>