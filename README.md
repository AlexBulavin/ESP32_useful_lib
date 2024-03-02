# ESP32_useful_lib
Полезные библиотеки для ESP32

WiFi_multi_SSID_setup_and_settings.rtf содержит шаблон для настройки работы ESP32 c несколькими WiFi точками. Разумеется выбирается только одна, но из набора нескольких.
Названия точек нужно сохранить в массиве:
const char* ssid[] = {"First WiFi net", "Second  WiFi net"}; //Вместо "First WiFi net", "Second  WiFi net" введите названия своих WiFi точек (SSID). При необходимости дополните.
const char* password[] = { "Pass from First WiFi net", "Pass from Second WiFi net"};//Вместо "Pass from First WiFi net", "Pass from Second WiFi net" введите пароли своих WiFi точек, соответствующие "First WiFi net", "Second WiFi net" названиям. При необходимости дополните.
