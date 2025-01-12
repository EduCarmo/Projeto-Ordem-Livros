<script>
    import Menu from "./Menu.svelte";
    import MenuItem from "./MenuItem.svelte";
</script>

<aside
    class="
    flex flex-col self-start gap-10 w-72
    border border-zinc-800 rounded-md p-5
    "
>
    <Menu titulo="Navegação">
        <MenuItem texto="Início" href="/" />
        <MenuItem texto="Personagens" href="/" />
        <MenuItem texto="Autores" href="/autores" />
        <MenuItem texto="Séries" href="/" />
    </Menu>
    <Menu titulo="Principais Autores">
        <MenuItem texto="J.K. Rowling" href="/" />
        <MenuItem texto="J.R.R. Tolkien" href="/" />
        <MenuItem texto="George R.R. Martin" href="/" />
    </Menu>
    <Menu titulo="Outras Categorias">
        <MenuItem texto="últimas Notícias" href="/" />
        <MenuItem  texto="Séries Populares" href="/"/>
        <MenuItem texto="Faacebook" href="/"/>
        <MenuItem texto="Instagram" href="/"/>
        <MenuItem texto="Youtube" href="/"/>
    </Menu>
</aside>
