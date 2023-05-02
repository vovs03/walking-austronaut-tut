# Dev_flow

## Create Animations in Atlas-file

> `.\main\austronaut.atlas`

1. Add into Atlas `Animation Group` :
	- left
	- right
	- back
	- front
2. Set images inside each group.
3. Set Speed `From 60 to 12`

<img width="480" alt="Screenshot 2023-05-02 at 13 05 40" src="https://user-images.githubusercontent.com/21124057/235639297-5d0b4677-fb1e-4289-a368-46f8149a667e.png">

---

## Android

Для проверки работы приложения на девайсе с андроидом необходимо проделать следующие шаги:

1. Установить устройство в режим `для разработчиков`
2. Там же установить **режим** `Отладка по USB`
3. В ОС дб. установлен `adb` (Tools)

Помнить, про состояние в процессе тестирования :a:`Install` `/` :b:`Uninstall`

<details>
	<summary>Error Package com.example.todo signatures do not match the previously installed version; ignoring!</summary>

	> https://stackoverflow.com/questions/41709102/package-signatures-do-not-match-the-previously-installed-version

   - :a:: `adb install "com.domain.yourapp"`
   - :b:: `adb uninstall "com.domain.yourapp"`

</details>



