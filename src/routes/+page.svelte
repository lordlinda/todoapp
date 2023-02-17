<script>
    import TodoItem from "../lib/todo-item.svelte";
    const title = "Todos"
</script>
<svelte:head>
<title>{title}</title>
</svelte:head>
<h1>{title}</h1>
<form action="">
    <input type="text" aria-label="Add A Todo" placeholder="Type to add a todo">
</form>


