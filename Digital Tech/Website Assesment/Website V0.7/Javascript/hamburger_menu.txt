const hamburgerToggle = document.querySelector("#hamburger-toggle");
const header = document.querySelector("#header")


hamburgerToggle.addEventListener("click", onHamburgerClick);

function onHamburgerClick() {
    if (!header.classList.contains("open")) {
        header.classList.add("open");
    }
    else {
        header.classList.remove("open");
    }
}