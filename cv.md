# Irina Goroshchik
## Contacts
* Location: *Minsk, Belarus*
* Email: *ira.goroshchik@mail.ru*
* GitHub: *[IraGoroshchik](https://github.com/IraGoroshchik)*
## About me
A hardworking, purposeful and conscientious frontend developer with a great desire to create the client side of a website. I am ready to visualize your ideas.  I want to develop and grow further in this area.
## Skills
* Hard
    * HTML
    * CSS/SCSS
    * JS
* Soft
    * Openness to criticism
    * Teamwork
    * Adaptability
## Code Example
```
class WeatherBody {
    constructor(data) {
        this.date = data.dt_txt.slice(0, 16)
        this.iconWeather = data.weather[0].icon
        this.temp = Math.round(data.main.temp - 273) + ' °C';
        this.init()
    }

    init() {
        this.renderWeatherDay()
    }

    renderWeatherDay() {
        const template = `
            <section class="weatherDay">
                <div class="dayDate">
                    <span class="date">${this.date}</span>
                </div>
                <div>
                    <img src="http://openweathermap.org/img/wn/${this.iconWeather}@2x.png" class="dayIcon">
                </div>
                <div class="dayTemp">
                    ${this.temp}
                </div>
            </section>

        `
        container.innerHTML = container.innerHTML + template;
    }

}
```
## Experience

## Education
**University:** Belarusian National Technical University, specialty civil engineer \
**Courses:**
* Myfreedom 2020 (frontend developer)
## English
**A1**
