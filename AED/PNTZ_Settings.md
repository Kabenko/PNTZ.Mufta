## Настройки связи
Параметры:	38400, even, 8, 1	

Адрес уст-ва:	31

Интерфейс:	RS-422		

## Описание
Диапазон значений датчика, передаваемых от AED в ПЛК Easy 0-20 000 (формат COF6), что соответствует весу 0-номинальное значение в кг (Н). Формат значений — Двоичный, два байта, диапазон до 20 000. Пользовательская х-ка LDW LWT отсутствует (по умолчанию). 
Параметры SZA SFA — заводская калибровка датчика, менять не надо. Плата на ПНТЗ работает в режиме постоянной передачи текущего веса, запускается цикл командой MSV?0;. 
Младший байт впереди. Никаких других доп символов платой в этом режиме не передается, только два байта текущего веса
## Настройки платы AED (дамп настроек с ПНТЗ)
Настройки платы хранятся в xml файлах в этом разделе
|	Name	|	ID	|	Value	|	ns0:type	|	Комментарий	|
|-|-|-|-|-|
|	TYP	|	2404355	|	64	|	xsd:int	|		|
|	IDN	|	3145534	|	HBM,AD103C         ,107855 ,P77	|	xsd:string	|		|
|	IDN1	|	2433025	|	AD103C	|	xsd:string	|		|
|	---	|	2490389	|	107855	|	xsd:int	|		|
|	FWT	|	2232327	|	0	|	xsd:int	|	Номинальный вес (вес заполнения)	|
|	ADR	|	2490369	|	31	|	xsd:int	|	Адрес	|
|	---	|	2490370	|	63	|	xsd:int	|		|
|	GRU	|	2490377	|	32	|	xsd:int	|		|
|	BDR1	|	2490371	|	38400	|	xsd:int	|	Скорость	|
|	BDR2	|	2490372	|	1	|	xsd:int	|	Четность (да, нет)	|
|	---	|	2490373	|	125000	|	xsd:int	|		|
|	---	|	2490374	|	1	|	xsd:int	|		|
|	COF	|	2490375	|	6	|	xsd:int	|	Установка выходного формата	|
|	CSM	|	2490376	|	0	|	xsd:int	|	Контрольная сумма	|
|	STR	|	2490378	|	0	|	xsd:int	|	Включить оконечные резисторы	|
|	SZA	|	2162690	|	53	|	xsd:int	|	Регулировка точки нуля	|
|	SFA	|	2162689	|	820156	|	xsd:int	|	Регулировка точки полной шкалы	|
|	GCA	|	2359297	|	981029	|	xsd:int	|		|
|	GDE	|	2359299	|	981029	|	xsd:int	|		|
|	---	|	2183169	|	0	|	xsd:int	|		|
|	---	|	2183170	|	1000000	|	xsd:int	|		|
|	---	|	2183171	|	0	|	xsd:int	|		|
|	---	|	2183172	|	0	|	xsd:int	|		|
|	---	|	2387969	|	100000	|	xsd:int	|		|
|	---	|	2387970	|	0	|	xsd:int	|		|
|	---	|	2387971	|	0	|	xsd:int	|		|
|	---	|	2400257	|	0	|	xsd:int	|		|
|	---	|	2400258	|	0	|	xsd:int	|		|
|	---	|	2400259	|	0	|	xsd:int	|		|
|	---	|	2383873	|	0	|	xsd:int	|		|
|	---	|	2392065	|	0	|	xsd:int	|		|
|	---	|	2392066	|	0	|	xsd:int	|		|
|	---	|	2392067	|	0	|	xsd:int	|		|
|	---	|	2383874	|	0	|	xsd:int	|		|
|	---	|	2396161	|	0	|	xsd:int	|		|
|	---	|	2396162	|	0	|	xsd:int	|		|
|	---	|	2396163	|	0	|	xsd:int	|		|
|	LDW	|	2166790	|	0	|	xsd:int	|	Вес мертвой нагрузки	|
|	LWT	|	2166791	|	1000000	|	xsd:int	|	Номинальная нагрузка датчика	|
|	LIC1	|	2170881	|	0	|	xsd:int	|	Коэффициенты линеаризации	|
|	LIC2	|	2170882	|	1000000	|	xsd:int	|	Коэффициенты линеаризации	|
|	LIC3	|	2170883	|	0	|	xsd:int	|	Коэффициенты линеаризации	|
|	LIC4	|	2170884	|	0	|	xsd:int	|	Коэффициенты линеаризации	|
|	CWT1	|	2166785	|	1000000	|	xsd:int	|	Калибровочный вес	|
|	CWT2	|	2166786	|	1000000	|	xsd:int	|	Калибровочный вес	|
|	DPT	|	2166787	|	0	|	xsd:int	|	Десятичная точка	|
|	NOV	|	2166794	|	0	|	xsd:int	|	Номинальное значение	|
|	RSN	|	2166795	|	1	|	xsd:int	|	Разрешение выходного значения	|
|	ENU	|	2433028	|		|	xsd:string	|	Единицы измерения	|
|	FMD	|	2101253	|	0	|	xsd:int	|	Режим фильтра	|
|	ASF	|	2101249	|	1	|	xsd:int	|	Цифровой фильтр	|
|	HSM	|	2166789	|	0	|	xsd:int	|	Высокоскоростной режим работы АЦП	|
|	ICR	|	2101254	|	0	|	xsd:int	|	Внутренняя скорость преобразования	|
|	---	|	2404353	|	1	|	xsd:int	|		|
|	FTL	|	2408453	|	10	|	xsd:int	|		|
|	NTF1	|	2408454	|	0	|	xsd:int	|	Режекторный фильтр (для FMD2, ..3,.. 4)	|
|	NTF2	|	2408455	|	0	|	xsd:int	|	Режекторный фильтр (для FMD2, ..3,.. 4)	|
|	POR	|	2105347	|	3	|	xsd:int	|	Управление дискретными входами/выходами	|
|	RIO	|	2105362	|	1027	|	xsd:int	|	Чтение состояния дискретных входов/выходов	|
|	---	|	2379777	|	0	|	xsd:int	|		|
|	LIV11	|	2109441	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV12	|	2109442	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV13	|	2109443	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV14	|	2109444	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV21	|	2109445	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV22	|	2109446	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV23	|	2109447	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV24	|	2109448	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV31	|	2109449	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV32	|	2109450	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV33	|	2109451	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV34	|	2109452	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV41	|	2109453	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV42	|	2109454	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV43	|	2109455	|	0	|	xsd:int	|	Установка предельного значения	|
|	LIV44	|	2109456	|	0	|	xsd:int	|	Установка предельного значения	|
|	PVA1	|	2105348	|	1638400	|	xsd:int	|	Считывание пиковых значений (МИН / MAКС)	|
|	PVA2	|	2105349	|	-1638400	|	xsd:int	|	Считывание пиковых значений (МИН / MAКС)	|
|	PVS1	|	2105350	|	0	|	xsd:int	|	Установка пиковых значений (МИН / MAКС)	|
|	PVS2	|	2105351	|	1	|	xsd:int	|	Установка пиковых значений (МИН / MAКС)	|
|	FRS1	|	2097157	|	0	|	xsd:int	|	Текущий вес (результат дозирования)	|
|	FRS2	|	2097158	|	0	|	xsd:int	|	Текущий вес (результат дозирования)	|
|	CFT	|	2240513	|	0	|	xsd:int	|	Измерение продолжительности грубого потока	|
|	DST	|	2240515	|	0	|	xsd:int	|	Измерение времени дозирования 	|
|	FFT	|	2240516	|	0	|	xsd:int	|	Измерение продолжительности тонкого потока 	|
|	NDS	|	2240517	|	0	|	xsd:int	|	Счетчик циклов дозирования 	|
|	SDM	|	2240518	|	0	|	xsd:int	|	Среднее значение результата дозирования (за все циклы) 	|
|	SDS	|	2240519	|	0	|	xsd:int	|	Номинальное отклонение результата среднего значения 	|
|	SUM	|	2240520	|	0	|	xsd:int	|	Суммарный вес 	|
|	SDO	|	2949122	|	0	|	xsd:int	|	Статус дозирования (результат дозирования) 	|
|	CBK	|	2232321	|	0	|	xsd:int	|	Грубый поток, контроль разрыва мешка 	|
|	CFD	|	2232322	|	0	|	xsd:int	|	Точка отключения грубого потока 	|
|	EWT	|	2232323	|	0	|	xsd:int	|	Пустой вес 	|
|	FBK	|	2232324	|	0	|	xsd:int	|	Контроль разрыва мешка, тонкий поток 	|
|	FFD	|	2232325	|	0	|	xsd:int	|	Точка отключения тонкого потока 	|
|	FFM	|	2232326	|	0	|	xsd:int	|	Минимум подачи при тонком потоке 	|
|	LTL	|	2232328	|	0	|	xsd:int	|	Нижний порог допуска 	|
|	SYD	|	2232329	|	0	|	xsd:int	|	Систематическое отклонение 	|
|	UTL	|	2232330	|	0	|	xsd:int	|	Верхний порог допуска 	|
|	MSW	|	2232331	|	0	|	xsd:int	|		|
|	WDP	|	2228225	|	0	|	xsd:int	|	Сохранение параметров дозирования в EEPROM 	|
|	RDP	|	2228226	|	0	|	xsd:int	|	Чтение параметров дозирования из памяти (для следующего цикла дозирования)	|
|	DMD	|	2228228	|	0	|	xsd:int	|	Установка режима дозирования 	|
|	EMD	|	2228229	|	0	|	xsd:int	|	Режим опустошения 	|
|	OMD	|	2228230	|	0	|	xsd:int	|	Функции выходов 	|
|	OSN	|	2228231	|	0	|	xsd:int	|	Оптимизация вкл/выкл 	|
|	RDS	|	2228232	|	0	|	xsd:int	|	Перезапуск дозирования 	|
|	SDF	|	2228234	|	2	|	xsd:int	|	Функция контроля 	|
|	TMD	|	2228235	|	0	|	xsd:int	|	Режим тарирования 	|
|	VCT	|	2228236	|	0	|	xsd:int	|	Контроль вентилей грубого/тонкого потоков 	|
|	FNB	|	2228237	|	0	|	xsd:int	|	Запрос номера набора текущих параметров дозирования 	|
|	CBT	|	2236417	|	0	|	xsd:int	|	Контроль продолжительности грубого потока 	|
|	EPT	|	2236418	|	0	|	xsd:int	|	Время опустошения 	|
|	FBT	|	2236419	|	0	|	xsd:int	|	Контроль продолжительности тонкого потока 	|
|	LTC	|	2236420	|	0	|	xsd:int	|	Время блокировки грубого потока 	|
|	LTF	|	2236421	|	0	|	xsd:int	|	Время блокировки тонкого потока 	|
|	MDT	|	2236422	|	0	|	xsd:int	|	Максимальное время дозирования 	|
|	RFT	|	2236423	|	0	|	xsd:int	|	Время послесыпи 	|
|	STT	|	2236424	|	0	|	xsd:int	|	Время стабилизации 	|
|	TAD	|	2236425	|	0	|	xsd:int	|	Задержка тарирования 	|
|	FFL	|	2236426	|	0	|	xsd:int	|	Время тонкого потока 	|
|	TYP	|	2404355	|	64	|	xsd:int	|		|
|	---	|	2433026	|	HBM	|	xsd:string	|		|
|	MSV1	|	2097153	|	492	|	xsd:int	|	Вывод измеренного значения 	|
|	MSV2	|	2097154	|	8	|	xsd:int	|	Вывод измеренного значения 	|
|	CDL	|	2101251	|	0	|	xsd:int	|	Обнуление мертвой нагрузки (+/-2 % от измеряемого диапазона)	|
|	TAS	|	2113538	|	0	|	xsd:int	|	Переключение Брутто/Нетто 	|
|	TAV	|	2113539	|	-6826	|	xsd:int	|	Ввод величины тарировки 	|
|	ESR	|	2097159	|	48	|	xsd:int	|	Сообщение об ошибке 	|
|	AOV	|	2424833	|	6	|	xsd:int	|	Переполнение счетчика АЦП 	|
|	SOV	|	2424834	|	0	|	xsd:int	|	Сообщение о выхода сигнала с датчика за максимальный предел измерения	|
|	---	|	2424835	|	7000000	|	xsd:int	|		|
|	---	|	3145523	|	0	|	xsd:int	|		|
|	APD	|	2490383	|	0	|	xsd:int	|		|
|	IMD	|	2101255	|	0	|	xsd:int	|		|
|	EMA	|	2424836	|	0	|	xsd:int	|		|
|	EMB	|	2424837	|	0	|	xsd:int	|		|
|	TEX	|	2490379	|	172	|	xsd:int	|	Выбор разделителя 	|
|	BOF	|	2490382	|	0	|	xsd:int	|		|
|	---	|	2490384	|	0	|	xsd:int	|		|
|	TMP	|	2383875	|	203776	|	xsd:int	|		|
|	---	|	2490381	|	0	|	xsd:int	|		|
|	MAV1	|	2097155	|	-8388608	|	xsd:int	|	Вывод измеренного по срабатыванию триггера значения	|
|	MAV2	|	2097156	|	0	|	xsd:int	|	Вывод измеренного по срабатыванию триггера значения	|
|	CDT	|	2101259	|	0	|	xsd:int	|		|
|	TRC1	|	2105352	|	0	|	xsd:int	|	Установки триггера 	|
|	TRC2	|	2105353	|	0	|	xsd:int	|	Установки триггера 	|
|	TRC3	|	2105354	|	0	|	xsd:int	|	Установки триггера 	|
|	TRC4	|	2105355	|	0	|	xsd:int	|	Установки триггера 	|
|	TRC5	|	2105356	|	0	|	xsd:int	|	Установки триггера 	|
|	TRF	|	2105357	|	1000000	|	xsd:int	|	Коррекция значения измеренного по срабатыванию триггера	|
|	TRM	|	2105358	|	0	|	xsd:int	|	Среднее значение измерений по срабатыванию триггера	|
|	TRN	|	2105359	|	0	|	xsd:int	|	Количество измерений по срабатыванию триггера 	|
|	TRS	|	2105360	|	0	|	xsd:int	|	Номинальное отклонение измеренного по срабатыванию триггера значения	|
|	---	|	2105361	|	15	|	xsd:int	|		|
|	---	|	3145529	|	0	|	xsd:int	|		|
|	---	|	3145532	|	0	|	xsd:int	|		|
|	CRC	|	2293761	|	0	|	xsd:int	|	Контрольная сумма 	|
|	LFT	|	2293762	|	0	|	xsd:int	|	Торговое применение 	|
|	TCR	|	2293763	|	0	|	xsd:int	|	Торговый счетчик 	|
|	DZT2	|	2101252	|	0	|	xsd:int	|	Динамическое отслеживание нуля 	|
|	ZSE	|	2101256	|	0	|	xsd:int	|	Установка нуля при включении 	|
|	ZTR	|	2101257	|	0	|	xsd:int	|	Автоматическое отслеживание нуля 	|
|	DZT1	|	2101258	|	0	|	xsd:int	|	Динамическое отслеживание нуля 	|
|	HRN	|	2166788	|	0	|	xsd:int	|		|
|	MRA	|	2166792	|	0	|	xsd:int	|	Переключатель диапазона измерения 	|
|	MTD	|	2166793	|	0	|	xsd:int	|	Отслеживание колебаний 	|
