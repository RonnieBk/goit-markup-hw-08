https://ronniebk.github.io/goit-markup-hw-07/

@media (min-width: 768px) {
.menu-toggle {
display: none;
}
}

.menu-toggle:hover,
.menu-toggle:focus {
background-color: rgba(0, 0, 0, 0.1);
}

.menu-container {
position: fixed;
top: 0;
left: 0;
width: 100vw;
height: 100vh;
padding: 32px;
background-color: #3f51b5;
z-index: 999;

transform: translateX(100%);
transition: transform 250ms ease-in-out;
}

.menu-container.is-open {
transform: translateX(0);
}

.menu-container .menu-toggle {
position: absolute;
top: 16px;
right: 16px;
color: #fff;
}
