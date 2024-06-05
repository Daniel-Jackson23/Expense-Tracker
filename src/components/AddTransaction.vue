<template>
    <h3>Add New Transaction</h3>
    <form id="form">
        <div class="form-control">
            <label for="text">Text</label>
            <input type="text" id="text" placeholder="Enter Text...">
        </div>
        <div class="form-control">
            <label for="amount">
                Amount <br>
                (negative - expense, positive - Income)
            </label>
            <input type="number" id="amount" placeholder="Enter Amount...">
        </div>
        <button class="btn">Add Transaction</button>
    </form>
</template>

<script>
</script>