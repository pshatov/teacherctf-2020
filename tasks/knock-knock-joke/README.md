# Knock-Knock Joke

## Описание

Я думал, что CTF — это трагедия. Но сейчас понял, что это комедия.

## Решение

Внутри картинки спрятан zip-архив (под windows необходимо сменить расширение файла на .zip, чтобы распаковать этот архив). Он защищён паролем, но пароль можно найти в exif картинки (в поле user comment) или просто угадать, исходя из названия таска: knockknock. В архиве лежит файл flag.txt с флагом.

**Флаг:** TeacherCTF{y0u_g0t_1t!}
