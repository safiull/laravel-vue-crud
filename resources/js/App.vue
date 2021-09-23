<template>
    <div class="container">
        <div class="card">
            <div class="card-body">
                <nav class="navbar navbar-expand-lg navbar-light bg-light">
                    <div class="collapse navbar-collapse">
                        <div class="navbar-nav">
                            <router-link to="/" class="nav-item nav-link">Products List</router-link>
                            <router-link to="/create" class="nav-item nav-link">Create Product</router-link>
                        </div>
                    </div>
                </nav>
            </div>
        </div>

        <router-view> </router-view>
    </div>
</template>

<script>
    export default {}
</script>
