# Iryna Nyzka (NoName)

---

### Junior Frontend Developer

![my photo](./img/my-photo.JPG "my photo")

---

### Contact Info

- **Phone:** +38 096 471 89 35
- **Discord:** No Name (Noneif)#7194
- **E-mail: sofar0222@gmail.com**
- **LinkedIn: [NoName](https://www.linkedin.com/in/no-name-181abb234/)**
- **Website: [personal.netlify.app](https://musical-cupcake-a8f1f8.netlify.app/)**
- **GitHub: [@Noneif](https://github.com/Noneif)**
- **Instagram: [@NoName](https://www.instagram.com/bams_boooooooooo/)**

---

**Brief info about me:** a kitchen nerd and funkiller, but a good person.

**About the desire to learn and learn new things:** since childhood, I have liked to spend time with different tools, disassemble, assemble and upgrade various appliances, but to carry out such manipulations without studying the “research subjects” is almost impossible and not even interesting. In programming, these conventions are also present.

**Why programming?** - Home appliances are over.

**An interesting fact:** most of my life I wander around different educational institutions, I didn’t quit any, all of them were with sheepskin.

---

### Skills

- HTML
- CSS
- JavaScript
- Bootstrap
- Figma
- Responsive Web Design
- VS Code
- Git, GitHub
- React.js
- Netlify

---

### Code Example

```
function addForecastDays(parameter) {
  let htmlElement = document.querySelector("#forecast");
  let addHtml = `<div class="row six-days">`;
  let days = parameter.data.daily;
  days.forEach(function (dayForecast, index) {
    if (index > 0 && index < 6) {
      addHtml =
        addHtml +
        `<div class="col-4 col-md-2 justify-content-center p-2 text-center">
                <p class="day">${fixDayDisplay(dayForecast.dt)}</p>
                <img
                  src="http://openweathermap.org/img/wn/${
                    dayForecast.weather[0].icon
                  }@2x.png"
                  alt="${dayForecast.weather[0].description}"
                  width="50px"
                  class="day-sign"
                  id="day-sign"
                />
                <p class="day-temp">
                  <span class="day-temp-min">${Math.round(
                    dayForecast.temp.min
                  )}°</span><span class="day-temp-max"> ${Math.round(
          dayForecast.temp.max
        )}°</span>
                </p>
              </div>`;
    }
  });
  addHtml = addHtml + `</div>`;
  htmlElement.innerHTML = addHtml;
}
```

---

### Experience

- **[Guitar Project](https://hilarious-biscochitos-e7149d.netlify.app/)**
  **Tech Stack:** HTML, CSS, JavaScript
- **[Weather App](https://enchanting-gaufre-9b6641.netlify.app/)**
  **Tech Stack:** HTML, CSS, Bootstrap, JavaScript, Axios, Geolocation API, Open Weather API
- **[React Weather App](https://vocal-shortbread-8d1e02.netlify.app/)**
  **Tech Stack:** HTML, CSS, Bootstrap, JavaScript, React.js, Axios, Open Weather API
- **[React Dictionary App](https://super-platypus-385764.netlify.app/)**
  **Tech Stack:** HTML, CSS, Bootstrap, JavaScript, React.js, Axios, Free Dictionary API, Pexels API

---

### Education

**Universities:**

- **Dnipro Transport and Economic College (Law)** – 2006-2010, Ukraine, Junior Specialist
- **Yaroslav Mudryi National Law University (Faculty of Justice)** – 2010-2014, Ukraine, Bachelor
- **Yaroslav Mudryi National Law University (Faculty of Business Law)** – 2014-2015, Ukraine, Master
- **Mykolas Romeris University (International Public Law)** – 2015-2016, Lithuania, Master

**Certifications:**

- **[SheCodes Basics](https://www.shecodes.io/certificates/f2dd698bac6df7f22beb69154cb164c3)**
- **[SheCodes Plus](https://www.shecodes.io/certificates/0b56b536b045c35f04b2269ecc88bd4d)**
- **[SheCodes Responsive](https://www.shecodes.io/certificates/2ed8064a3bfef16ad9c969417b244735)**
- **[SheCodes React](https://www.shecodes.io/certificates/45bcef3bb686abdba86c1a4048e20fa2)**

---

### Languages

- English (B1-B2)
- Dutch (A1)
- Russian (C2)
- Ukrainian (C2)
