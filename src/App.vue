<script>
import ToDoItem from "./components/ToDoItem.vue"

export default {
    name: "app",
    components: {
        ToDoItem,
    }
}

    
</script>

<template>
    <div id="app">
        <h1>My To-Do List</h1>
        <ul>
            <li>
                <to-do-item label="My ToDo Item" :done="false"></to-do-item>
            </li>
        </ul>
    </div>
</template>

<style>
</style>
