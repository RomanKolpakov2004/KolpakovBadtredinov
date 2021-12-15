# KolpakovBadtredinov
1) Отладка отдельных модулей - Отладка - это процесс устранения ошибок в коде Вашей программы. Как уже упомянули выше, производиться она может как при помощи каких-то инструментов (отладчика, профайлера), так и путем вывода сообщений на консоль или в лог-файл, или просто путем наблюдений за поведением программы после запуска и фиксированием того факта, что некая часть работает отлично от Ваших ожиданий.
2) Тестировании программного модуля – Процесс тестирования программных модулей состоит в проверке корректности обработки модулями поступающей информации и получающихся на выходе данных в соответствии с функциями, представленными в спецификациях требований. Должна быть проверена корректность структуры модулей и примененных...
3) Принципы и виды отладки программного средства.
При отладке ПС отыскиваются и устраняются, в основном, те ошибки, наличие которых в ПС устанавливается при тестировании. Но нельзя гарантировать, что тестированием ПС практически выполнимым набором тестов можно установить наличие каждой имеющейся в ПС ошибки. Поэтому возникает две задачи. Первая задача: подготовить такой набор тестов и применить к ним ПС, чтобы обнаружить в нем по возможности большее число ошибок. Однако чем дольше продолжается процесс тестирования (и отладки в целом), тем большей становится стоимость ПС. Отсюда вторая задача: определить момент окончания отладки ПС (или отдельной его компоненты). Признаком возможности окончания отладки является полнота охвата пропущенными через ПС тестами множества различных ситуаций, возникающих при выполнении программ ПС, и относительно редкое проявление ошибок в ПС на последнем отрезке процесса тестирования. Последнее определяется в соответствии с требуемой степенью надежности ПС, указанной в спецификации его качества.Оптимальная стратегия проектирования тестов включает проектирование значительной части тестов по спецификациям, но она требует также проектирования некоторых тестов и по текстам программ. При этом в первом случае эта стратегия базируется на принципах:
на каждую используемую функцию или возможность - хотя бы один тест,
на каждую область и на каждую границу изменения какой-либо входной величины - хотя бы один тест,
на каждую особую (исключительную) ситуацию, указанную в спецификациях, - хотя бы один тест.
Оптимальную стратегию проектирования тестов можно конкретизировать на основании следующего принципа: для каждого программного документа (включая тексты программ), входящего в состав ПС, должны проектироваться свои тесты с целью выявления в нем ошибок.
