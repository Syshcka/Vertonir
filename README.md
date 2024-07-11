/*
* Фикс юникода в CMD
* Просто импортируйте этот файл.
* https://t.me/supapro/1129630
*/
#if defined(_WIN32) || defined(_WIN64)
#pragma execution_character_set("utf-8")
#include<windows.h>
const auto _dummy_ = []() {
    SetConsoleCP(65001);
    SetConsoleOutputCP(65001);
    return 0;
}();
#endif# Vertonir
