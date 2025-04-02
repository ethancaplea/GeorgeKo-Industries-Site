<template>
    <div>

        <!-- header -->
        <header>
            <nav>
                <ul>
                    <li><nuxt-link to="/">Home</nuxt-link></li>
                    <li><nuxt-link to="/contact">Contact</nuxt-link></li>
                </ul>
            </nav>
        </header>

        <!-- page contents -->
        <main>
            <slot />
        </main>

        <!-- footer -->
        <footer>
            <p>FOOTER </p>
        </footer>

    </div>
</template>