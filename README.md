# How to use

## Data
1. Add `weatherwidget.lib` to domain.

2. Add a `Panel.DataServer` to your project if it doesn't exist.

3. Insert one or more `WeatherClass` at your `DataServer` (one for each city of interest).

4. Configure the following properties:
    * **AppID** - Your unique API key (you can always find it on your account page under the ["API key" tab](https://home.openweathermap.org/users/sign_in).
    * **Lang** - Output in your language.
    * **Latitude** - Latitude city geo location.
    * **Longiude** - Longiude city geo location.
    * **RepeatInterval** - API query refresh time (in seconds).
    * **Units** - Temperature unit. 
        - `(I)` Imperial: Fahrenheit.
        - `(M)` Metric: Celsius

## Widget
1. Add `WidgetWeather` to your screen and associate it with `WeatherClass`.
2. Style the `WidgetWeather` as you wish.