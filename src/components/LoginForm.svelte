<script>
    const handleSubmit = () => {
        console.log("submitting")
    }
</script>

<form on:submit|preventDefault={handleSubmit}>
    <label for="">Email:</label>
    <input type="email" name="email">
    <label for="">Password:</label>
    <input type="password" name="password">

    <button>Login</button>

</form>

<style>
    form {
        color: var(--primary-light);
        display: flex;
        flex-direction: column;
        width: 80%;

    }
    label {
        font-weight: bold;
        font-size: 1.1em;
    }
    input {
        width: 100%;
        outline: none;
        background-color: inherit;
        border: none;
        border-bottom: 2px solid var(--primary-light);
        color: var(--primary-light)
    }
    input:focus {
        border-bottom: 2px solid var(--contrasting-orange);
    }
    button {
        margin-top: 4rem;
        color: var(--primary-light);
        background-color: var(--contrasting-orange);
        outline: none;
        border: none;
        font-weight: bold;
        font-size: 1.3em;
        border-radius: 5px;
        text-transform: uppercase;
    }
</style>