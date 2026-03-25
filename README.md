# **Ion Builder Game ⚛️**

An interactive, web-based educational simulation designed to teach chemistry students how atoms form stable ions. By manually adding or removing electrons, students explore the octet rule, valence shells, and the calculation of net atomic charges.

## **🎯 Educational Objectives**

This simulator helps students visualize and understand:

* **The Octet Rule:** Why atoms strive for a full outer shell (usually 8 electrons, or 2 for the innermost shell).  
* **Cations vs. Anions:** How losing electrons creates positive ions (cations) and gaining electrons creates negative ions (anions).  
* **Net Charge Calculation:** The mathematical relationship between Protons (+) and Electrons (-).  
* **Periodic Trends:** By walking through the first 20 elements (Hydrogen to Calcium), students can observe repeating patterns in valence electrons.  
* **Energy Limits:** Understanding why atoms rarely form ions with charges greater than \+4 or \-4.

## **✨ Features**

* **Interactive SVG Visualization:** Real-time visual updates of the atom's nucleus, electron shells, and individual electrons as users interact with the simulation.  
* **First 20 Elements:** Fully supports sequential navigation through elements 1 (Hydrogen) to 20 (Calcium).  
* **Smart Stability Checking:** Mathematical evaluation verifies if the current electron configuration matches a stable noble gas configuration or a valid exception (like H⁺).  
* **Immediate Feedback:** Provides contextual hints (e.g., warning students if they try to create chemically impossible ions like Li⁷⁻) and congratulatory messages with correct standard ion notation (e.g., ![][image1]).  
* **Fully Responsive:** Adapts seamlessly to mobile, tablet, and desktop screens.  
* **Accessible Design:** Meets WCAG AAA contrast requirements, includes full ARIA labeling, focus rings for keyboard navigation, and a live screen-reader announcer for visually impaired users.

## **🚀 Getting Started**

This project is built as a zero-dependency, single-file web application.

### **Prerequisites**

* A modern web browser (Chrome, Firefox, Safari, Edge).  
* An active internet connection (only required to fetch the Tailwind CSS CDN on the first load).

### **Installation & Usage**

1. Download or clone the repository.  
2. Locate the ion\_builder.html file.  
3. Double-click the file to open it in your default web browser. No server or build process is required\!

## **🛠️ Technical Stack**

* **HTML5:** Semantic structure and accessible UI elements.  
* **Vanilla JavaScript:** Handles game state, stability logic, DOM manipulation, and dynamic SVG generation.  
* **Tailwind CSS (via CDN):** Used for rapid, responsive, and modern styling.  
* **SVG (Scalable Vector Graphics):** Used to render crisp, infinitely scalable atomic models dynamically through JavaScript.

## **🎮 How to Play**

1. **Observe the Atom:** The screen displays a neutral atom. Note its Atomic Number, Protons, and current Electrons.  
2. **Modify Electrons:** Use the **Add Electron** (+) or **Remove Electron** (-) buttons to change the number of electrons in the valence shell.  
3. **Check Your Work:** Click **Check Stability**.  
   * If the outer shell is full and the charge is chemically viable, the shell will glow green, and the correct ion notation will be displayed\!  
   * If not, read the feedback hint and try again.  
4. **Navigate:** Use the **Next** and **Previous** buttons to explore different elements on the periodic table.

## **🤝 Contributing**

Contributions, issues, and feature requests are welcome\!

Potential future enhancements could include:

* Adding a "Compound Builder" mode to combine formed ions into neutral ionic compounds (e.g., combining ![][image2] and ![][image3] to make ![][image4]).  
* Transition animations for electrons jumping between shells.  
* Support for transition metals and variable oxidation states.

*Designed for interactive chemistry education.*

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADEAAAAZCAYAAACYY8ZHAAADC0lEQVR4Xu2WS0iUURiGZ9Du90hM5/KP48AU06IYKoR2uYkoWhQVtiuxIBIkEIIgiDbRQkQiwrCIFkVkEC4CF4ESQpuIpFUQIUVBiwIDC7Ln7T/HjkcbZmqCEeaFl3POdzvfd27/H4lU8W8IgqABnofXk8lkp69fECD5URVi+i0U0u3bCKlU6pS1qziQ2Iempqas6TeQ7C3fRkB3segiMNwMr8IxVuUt7Q0Cr/XtLNLp9BpNbGyfwz7GKd/uT2hsbFxu+8TI43rBUc+gpCIIuoFAB3Q+cZqGn1SYb2cQRXcWfpMtPgdp99bX16/wDYtAlHl72JXAVwglFWGBwzl4xyS3z9cLQXgZD9FOwglfXyxIfAf+gxSx0cri8XhGi2KJ/gFtuyPbnc/nF7lxZoFgS3F6BHtNEfNdtqgKwLZDNnDINygGWnnQR9LrNS7LcRJisVgchzHYZRLs9220eplMZgmFDBQodBbmu1v4DsMTWl30R+if9m2EkosgYCsOgzpGpogh7Y7V19XVrUR3U/cH3Tj8zniXG8NBDb5HsXkHX6bCR6ATXlMcE9/lHj+AEJRShDlKKqAVpum/hxPaHemR5Rj3s/3Lgt87dR9VrRdKsXqkpz1pZXZhtIMMo455QWjBCt4BFybxEZKMOSs9iTxvEu9XIbJV8ibJDj+OgG4KvlEsR3apkE9ZkEgk9jPBPbq1eiqD8Mz+eqE0sTu5EoRf8dnuhJjBfCuO7IldFMe0vAjCF6nLjnWGlYxk8LbOsWP7A45rx6zMwjnvba48CI/nM4pY58rLhmw2u4rgj91LSr/bJHMFbnPtJfdX2sIcxTm7VMinHNArcpdJXjPxloiZJBm+VFrxYcdWX9etyKakt7Y+gvDVOqY+z/HqIPx4FvoD+HsoqAk+7XDU0b3SdyGXyy0mqYeeneWcp5FCDyP/CL/Qf4HvGfoj2nHfdsGAAtpgry+vWDQ3NydoahyRflMG9Po5ssoFq90CpzhCm8wvzHH4GT71bSsZuvg7g/D/S7yscWT2zlRRRRX/ET8BvkDsH+aSoJUAAAAASUVORK5CYII=>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAZCAYAAACy0zfoAAACEElEQVR4Xu2VzStEURjGTShCImMyZubMnVlMFj7qrigrNjaSKIWtUlb+ACnZWE4WshElGymRRE2WViyVpWwsLC0kH8/TPXe8HXfGvbOYqPvU09zzvufjd95zz52amlD/VOl0etGM/RkppdbMmKfQcQy+TqVSD7RlWX0yn0wmh5E/hLddY+cDsk9Q+YZLJBK9gJqCtzDoEz5AuE7kuxGbhQvwO8Am4vF4h5gisHzDUQBrw4AzeIiAAFg1ukTQZ4eQRtyX9OaLxjxHRmzEHFMUOvcQTkOyenc43pibF/A9clylClQ5VgTO6+dHXb0ZNw84G7FLQn6P+qEIXoF227brzYSpoHB5AurnTcIB5ByLNepYEd5LyC3BT/ANxj3gd8Odz0u+4ZQ4UrYJRDACEvSXI41wIfSZk0GOxS0flzEp3xeKO1RGVXikGu5RH+lpLpdrkX0onXuRi8VisSbEnktsJpgIRkAZ42VA7E4D/oB3pcd+yhiAM4hdRaPRZhkPLB4ZqnQBmH4zx8+JhjuBJ808FyeEB9xoqc0EkjLeNyNnKefmeh6RgHuRcbTX+b4xj3kXKqogrzwmuoX3MplMq5mnkBssVwXl3NI3PvNdQ7V30f6AuwC2Ij9HvqUXfVXOsbleNvvx5pa7dQRKOf8c+wC5x/M8PI12Ae3jUpuuqlgpwDS47Ww224mfWtElVKhQoaqpL6LAlXS6KQBYAAAAAElFTkSuQmCC>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAZCAYAAAC/zUevAAAB1UlEQVR4Xu1VTStEYRS+txk1CiUu5uPO/ZjJNAqLy8bGStkQZecvzB+ws/EHrFlYKAspCxMbCSvKClmwYMFiklLsxHPMfXU6zTD3ThZ0n3q6vc8587znPe/HaFqEPwQ9nU53WZaV5KLneS18/FvQMfEO+Aa+g/e2bR+CdiaTacV4RSU6jjOM8UU2m71DeJF5hAeM+mC6he82JhyEFCMd2ix4hsn28H1W+alUqhu5M1SkaZrTX0ZhAIMRmFfAJ3BMxgnIGUXslXeCgMJcaA+FQqFdabQA6HN1OEEd5R6fwEpOqPX4LmCoyzgB8SR4C85znTpAv+VaKJAJeJ7L5XpkTIGK8IstCn2p6SJg4PhFlGSMg4qgdvJWGobRBv0AfOS5gYHVrcHkFBN0ythPUFsBLstYw2ArWdfqnIXvoLaiqZuhiqBuyBgHbRk6tZHP5zuUxrfCEuckKOIw2GygiJJ8jNTVpEKoIB4LDJoAhrs1764P5JRxc0yuifOgo0sGjweGVX2ib/AMD3EdxQ1AP9JqnBeaHHxBjocuTUKKy5xAgMk4DK/9lV2Bq+AleOy6br/MJ/j/GxX/7diX8bCIwazoP61TmKRXJkiggIRVfcQSMhYhQoR/gQ+HLXTRLMhAPQAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAZCAYAAAB3oa15AAADaUlEQVR4Xu1VTUhUURR+gxZF/5ANmnpnxgEJg4KBopJWbSSIshaRi9pEkVq77AeijYu2VpsQooXYj9QmpT/KCkpz06LBNkFEKS3MTS7C1L5v3rlvztx5atMy3geH+8453z333HPPfdfzIkT4f1BRUbHSGFOZTCbj2t7Q0LBU6/MikUhsRYBntbW1XzB+xNgOc0xzYL8I3i2MN6xwnuaUCiYN+QaZg/yAjGHts9XV1cuxGcOcsMY5yesr5LcbIwdM2AjSIcgZCTZZU1OzWVFisO2E/zTGKYyXMO6Nx+MrFOevwQSR2BXEmMF4LJVKrbE+2HoQ/zHGT5ARbGQL9OPMCTKh4xQBhC4EvCybGHWPtKqqaj3sm7StVGD+B8ZnpT3nlC3gv0AOiriPOnI6ITl1utwA9fX1q0B4yMrLbjmhTXOwaCNknbaVAlaecZHQ3Uwms8T1W4DTDJmQYsWw5k29oVCQDBnAZznGbtnAkOawEloPAzhrXZsFfCdZHKc9iyAbGOTlllPPQsaxkZTLDQBCC3cq3zsgvyCzilLOyim9AJi7CzKMOe+lhw9Arls/2xH6KKQXarmaWgSssx383fzmqWPONKQf9mUuNwe2BQgDRvW38aswy80IZw8CPMnP8sFjNf5lDNpCtWHW8vDdZfzen7+KIcCcPubB9V1fADgzID3V/c0/A2xDkGue34cdJuQSGf9SFiwAvUmSzZ0oKwe9nzbetfzsxYE5nyn8U7q+AOxtVsi1w9YGGZOKPgirApOCZNmrytYp9hbq8lAN0sbv/OxiyD1ptbrx26fPW6Dt+I/vgTS7Dtj4mrCStzG+DquCJNptdZUs34uM4uV+DIttAHMeOfO4fofmFEBu+Qszz/9dEqSEXiL6eIJWZ4/DNg4ZYUtibKIdnMPkum+LAxaTFz9XbWm9acRplMIcdPheGUiv4BhCddNeyMMCX68N4voI+GZUhZhA7g2hra6ubgO+k5aL5LdBn4IcgVpm7XzRkcd52PutjZBiDKbT6dUYr7IIgdPkf5VzSgoCWB4CDese14D/lPEfnXvgvZT78sb4p/DWc4qCJN7JWpP4voPxOeQ75rbzodNcz3+Tfhr/D3l/sfb7Z8hRVybyj1gZq690jVjCx37IUeO3bnAaLhiDsbwFOBEiRIgQoWT8AbesBFbE/XO8AAAAAElFTkSuQmCC>