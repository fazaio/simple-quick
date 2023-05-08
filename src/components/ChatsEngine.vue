<template>
    <section class="text-sm">
        <div class="relative bg-white my-3 text-left rounded shadow-md" style="width: 734px;height: 737px;">
            <ChatsList class="hidden" />
            <ChatsDetails />
        </div>
        <button><img src="../assets/icon/2.svg" width="42" /></button>
    </section>
</template>
<script setup>
import { defineComponent } from 'vue';
import ChatsList from './ChatsPiston/ChatsList.vue';
import ChatsDetails from './ChatsPiston/ChatsDetails.vue';

defineComponent({
    ChatsList,
    ChatsDetails
})
</script>