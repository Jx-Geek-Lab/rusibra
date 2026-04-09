# Snapshot #1: Project Rusibra - Base Protocols
# Снапшот №1: Проект Rusibra — Базовые протоколы

## EN: General Context
- **Project Name:** Rusibra (Marine Catamaran).
- **Goal:** Design, documentation, and registration (GIMS RF) for navigation from Russian inland waterways (Volga-Don) to the World Ocean.
- **Workflow:** The LLM acts as a co-engineer, providing technical data and documentation.
- **Data Persistence:** User saves snapshots to a GitHub repository in .md format to prevent context loss.

## RU: Общий контекст
- **Название проекта:** Rusibra (Морской катамаран).
- **Цель:** Проектирование, подготовка документации и регистрация (ГИМС РФ) для перехода из внутренних водных путей РФ (Волга-Дон) в Мировой океан.
- **Рабочий процесс:** LLM выступает в роли со-инженера, предоставляя технические данные и документацию.
- **Сохранение данных:** Пользователь сохраняет снапшоты в GitHub-репозиторий в формате .md для предотвращения утери контекста.

## EN: Documentation & Snapshot Rules
1. **On Demand Only:** Snapshots and GIMS documentation are generated ONLY upon explicit user request (not in every message).
2. **Bilingual Format:** All official project outputs (snapshots/docs) must be in Russian (for the user/authorities) and English (for LLM context consistency).
3. **Format:** Strict Markdown (.md) for easy repo management.

## RU: Правила формирования снапшотов и документации
1. **Только по запросу:** Снапшоты и документация для ГИМС формируются ТОЛЬКО по прямому запросу пользователя (не в каждом сообщении).
2. **Двуязычный формат:** Все официальные выходы проекта (снапшоты/доки) должны быть на русском (для пользователя/органов) и английском (для консистентности контекста LLM) языках.
3. **Формат:** Строгий Markdown (.md) для удобного управления репозиторием.

---
**Status:** Base protocols initialized. Ready for technical data.
**Статус:** Базовые протоколы инициализированы. Готов к приему технических данных.

# Snapshot #2: Rusibra Keelson & Rocker Geometry
# Снапшот №2: Геометрия кильсона и рокера Rusibra

## EN: Keelson Specifications
- **Total Length:** 11.8 meters.
- **Max Width:** 40 cm (provides rigid base for keel/mast and floor support).
- **Thickness:** 60 mm.
- **Material:** Laminated water-resistant plywood (3-6 mm layers).
- **Reinforcement:** Glass fiber with epoxy resin at high-stress areas (mast step and keel attachment points).

## RU: Спецификация кильсона
- **Общая длина:** 11.8 метра.
- **Максимальная ширина:** 40 см (жесткое основание для киля/мачты и опора для пайол).
- **Толщина:** 60 мм.
- **Материал:** Влагостойкая фанера, ламинированная слоями по 3-6 мм.
- **Армирование:** Стеклоткань на эпоксидной смоле в зонах концентрации нагрузок (степс мачты и узлы крепления киля).

## EN: Rocker Profile (Reference point: 5.9m from bow)
### Bow Section (Rise starts 1m from center, Max height 0.75m):
- 2m: 3.1 cm | 3m: 12.5 cm | 4m: 28.1 cm | 5m: 50.0 cm | 5.9m: 75.0 cm (WL level).
- **Design Intent:** Wave-piercing characteristics for sea navigation.

### Stern Section (Rise starts 2m from center, Max height 0.55m):
- 3m: 3.6 cm | 4m: 14.5 cm | 5m: 32.5 cm | 5.9m: 55.0 cm.
- **Design Intent:** Steering group protection and prevention of "stern suction".

## RU: Профиль рокера (Точка отсчета: 5.9 м от носа)
### Носовая секция (Подъем от 1 м от центра, макс. высота 0.75 м):
- 2 м: 3.1 см | 3 м: 12.5 см | 4 м: 28.1 см | 5 м: 50.0 см | 5.9 м: 75.0 см (уровень ВЛ).
- **Цель:** Характеристики волнореза (wave-piercing) для морских переходов.

### Кормовая секция (Подъем от 2 м от центра, макс. высота 0.55 м):
- 3 м: 3.6 см | 4 м: 14.5 см | 5 м: 32.5 см | 5.9 м: 55.0 см.
- **Цель:** Защита рулевой группы и предотвращение «засасывания» кормы.

# Snapshot #3: Rusibra Fin Keel Specification
# Снапшот №3: Спецификация киля-плавника Rusibra

## EN: Fin Keel Technical Data
- **Type:** Fin Keel (Symmetrical airfoil, NACA 0012-like).
- **Dimensions:** Length 3.5 m, Depth/Height 0.45 m.
- **Thickness:** Tapered from 200 mm (root) to 100 mm (tip).
- **Shape:** Elliptical planform with a 45-degree leading edge sweep.
- **Material:** Composite sandwich (Plywood + Fiberglass/Epoxy).
- **Mounting:** 8-10 M20 studs (Stainless steel or High-strength composite).

## RU: Технические данные киля-плавника
- **Тип:** Киль-плавник (Симметричный профиль, подобный NACA 0012).
- **Размеры:** Длина 3.5 м, Глубина/Высота 0.45 м.
- **Толщина:** Сужение от 200 мм (у корня) до 100 мм (у кончика).
- **Форма:** Эллиптическая в плане, угол наклона передней кромки — 45 градусов.
- **Материал:** Композитный сэндвич (Фанера + Стеклоткань/Эпоксидная смола).
- **Крепление:** 8-10 шпилек M20 (Нержавеющая сталь или высокопрочный композит).

## EN: Positioning & Balance
- **Location:** Central hull section, from 5.00 m to 8.5 m from the bow.
- **Center of Lateral Resistance (CLR):** Positioned at 6.75 m for optimal balance with the Center of Effort (CE).
- **Load Distribution:** Force is distributed across 4+ structural bulkheads/frames.

## RU: Расположение и балансировка
- **Расположение:** Центральная часть корпуса, в диапазоне от 5.00 м до 8.5 м от форштевня.
- **Центр бокового сопротивления (ЦБС):** Точка 6.75 м для обеспечения баланса с Центром парусности (ЦП).
- **Распределение нагрузки:** Нагрузка передается на 4 и более силовых шпангоута.

## EN: Design Rationale
- **3.5 m Length:** Balance between course stability and maneuverability in marinas.
- **45° Sweep:** Prevents entanglement with fishing nets and reduces impact loads.
- **Variable Thickness:** Maximizes structural strength at the root while minimizing hydrodynamic drag.

## RU: Обоснование конструкторских решений
- **Длина 3.5 м:** Баланс между курсовой устойчивостью и маневренностью в маринах.
- **Наклон 45°:** Предотвращает наматывание сетей и снижает ударные нагрузки при столкновении с препятствиями.
- **Переменная толщина:** Максимальная прочность в узле крепления при минимальном гидродинамическом сопротивлении.

# Snapshot #4: Rusibra Steering System Specification
# Снапшот №4: Спецификация системы рулевого управления Rusibra

## EN: Steering System Technical Data
- **Type:** Semi-balanced spade rudder (18-20% balance to reduce helm pressure).
- **Rudder Blade:** Dimensions 1.0 x 0.5 m, Foil profile NACA 0012 (Symmetrical).
- **Rudder Stock (Shaft):** AISI 316L Stainless Steel, Tube 60x5 mm.
- **Bearings:** Polymer sliding bearings (Caprolon/POM-C).
- **Position:** Stock center at 10.95 m from the bow (integrated with frame 10.9).

## RU: Технические данные системы рулевого управления
- **Тип:** Полуподвесной балансирный руль (Балансировка 18-20% для снижения нагрузки на штурвале).
- **Перо руля:** Размеры 1.0 х 0.5 м, Профиль NACA 0012 (Симметричный).
- **Баллер:** Нержавеющая сталь AISI 316L, Труба 60x5 мм.
- **Подшипники:** Полимерные подшипники скольжения (Капролон/ПОМ-С).
- **Позиция:** Центр баллера на отметке 10.95 м от форштевня (интеграция со шпангоутом 10.9).

## EN: Structural Components
- **Rudder Trunk:** Heavy-duty fiberglass tube, bonded with epoxy. Top edge is 150 mm above Waterline (WL).
- **Fixation:** Vertical lock via locking collar and tiller hub.
- **Tiller:** Removable 1.4 m emergency/primary tiller, through-bolt attachment to the stock head.

## RU: Конструктивные узлы
- **Гельмпортовая труба:** Толстостенный стеклопластик на эпоксидном компаунде. Верхний срез на 150 мм выше ватерлинии (ВЛ).
- **Фиксация:** Вертикальная фиксация стопорным кольцом и ступицей румпеля.
- **Румпель:** Съемный, длина 1.4 м, крепление сквозным болтом к голове баллера (основное или аварийное управление).

## EN: Rationale & Safety
- **Material Choice:** AISI 316L for impact toughness and reparability.
- **Safety Margin:** Rudder bottom edge is 200 mm above the keel sole, protected from grounding by the main keel.
- **Leverage:** Positioning at 10.95 m provides an optimal lever arm for maneuverability.

# Snapshot #5: Rusibra Bulkheads & Demountable System
# Снапшот №5: Шпангоуты и система разборности Rusibra

## EN: Structural Frames (Bulkheads)
- **Standard Spacing:** Approximately 1 meter (adjusted for beam locations).
- **Construction:** Bulkheads are notched to receive the 60mm keelson (interlocking joint).
- **Bridge Beam Support:** "Double Frame" system at bridge beam locations. The beam sits between two reinforced bulkheads.

## RU: Силовой набор (Шпангоуты)
- **Основной шаг:** Около 1 метра (корректируется в местах установки балок).
- **Конструктив:** Шпангоуты имеют пазы для врезки 60-мм кильсона (соединение «в замок»).
- **Опоры балок моста:** Система «двойного шпангоута». Балка укладывается между двумя усиленными рамками.

## EN: Demountable Connection (Bridge Beams)
- **Fastening:** 4 studs per beam connection point.
- **Locking Method:** Nuts are tightened and then sealed with epoxy/fiberglass layers.
- **Maintenance/Disassembly:** For disassembly, the protective composite layer is cut, and nuts are removed/cut off.
- **Benefit:** Combines the rigidity of a permanent bond with the possibility of transportation.

## RU: Система разборности (Силовые балки)
- **Крепление:** 4 шпильки на каждый узел крепления балки.
- **Фиксация:** Гайки затягиваются и герметизируются слоями стеклоткани на эпоксидной смоле.
- **Демонтаж:** Для разборки защитный композитный слой срезается, гайки откручиваются или спиливаются.
- **Преимущество:** Сочетает жесткость монолитного соединения с возможностью транспортировки судна.

## EN: Integration
- **Keelson-Frame Joint:** Keelson is notched into bulkheads to ensure longitudinal stiffness before skin application.

## RU: Интеграция
- **Узел Кильсон-Шпангоут:** Кильсон врезается в шпангоуты, обеспечивая продольную жесткость каркаса до момента обшивки.

## RU: Обоснование и безопасность
- **Выбор материала:** AISI 316L из-за ударной вязкости и высокой ремонтопригодности.
- **Защита:** Нижняя кромка руля на 200 мм выше подошвы киля, что защищает его при посадке на мель.
- **Плечо рычага:** Установка на 10.95 м обеспечивает оптимальный момент для маневрирования.

# Snapshot #6: Rusibra Bridge Beams Construction
# Снапшот №6: Конструкция силовых балок моста Rusibra

## EN: Bridge Beam Specifications
- **Geometry:** Square box section (Hollow beam).
- **Core Material:** Laminated plywood walls with internal stiffeners (ribs).
- **End Inserts:** Solid timber blocks at attachment points for compression resistance (stud mounting zones).
- **Assembly:** Bonded with epoxy resin and reinforced with fiberglass (2-3 layers externally).

## RU: Спецификация балок моста
- **Геометрия:** Квадратное коробчатое сечение (пустотелая балка).
- **Материал стенок:** Ламинированная фанера с внутренними ребрами жесткости.
- **Закладные элементы:** Цельный брус в торцах балок для сопротивления сжатию в зонах крепления шпильками.
- **Сборка:** Проклейка эпоксидной смолой и внешнее армирование стеклотканью в 2-3 слоя.

## EN: Structural Rationale
- **Box Section:** High torsional and bending stiffness-to-weight ratio.
- **Solid Inserts:** Prevents plywood crushing under high torque of the mounting studs.
- **Composite Skin:** Provides environmental protection and additional structural integrity.

## RU: Конструкторское обоснование
- **Коробчатое сечение:** Высокая жесткость на кручение и изгиб при малом весе.
- **Цельные вставки:** Предотвращают смятие фанеры под высоким моментом затяжки крепежных шпилек.
- **Композитная оболочка:** Обеспечивает защиту от внешней среды и дополнительную монолитность конструкции.

# Snapshot #7: Rusibra Hull Dimensions & Flare
# Снапшот №7: Размерения корпуса и развал бортов Rusibra

## EN: Hull Dimensions (Single Pontoon)
- **Length Overall (LOA):** 11.8 m.
- **Waterline Width (Bwl):** 1.1 m.
- **Maximum Width (Bmax):** 1.4 m (at the "flare/lip" level).
- **L/B Ratio:** ~10.7 (high efficiency, low wave resistance).

## RU: Размерения корпуса (Один поплавок)
- **Общая длина (LOA):** 11.8 м.
- **Ширина по ватерлинии (Bwl):** 1.1 м.
- **Максимальная ширина (Bmax):** 1.4 м (на уровне «губы»/развала бортов).
- **Коэффициент удлинения (L/B):** ~10.7 (высокая эффективность, низкое волновое сопротивление).

## EN: Flare Geometry (The "Lip")
- **Vertical Start:** 10 cm above the Waterline (WL).
- **Outward Extension:** 15 cm on each side (total +30 cm to width).
- **Function:** Increases reserve buoyancy and usable internal volume while keeping a narrow entry for speed.

## RU: Геометрия развала бортов («Губа»)
- **Начало по вертикали:** 10 см выше ватерлинии (ВЛ).
- **Расширение:** по 15 см на каждую сторону (всего +30 см к ширине).
- **Функция:** Увеличение запаса плавучести и полезного внутреннего объема при сохранении узкого входа в воду для скорости.

# Snapshot #8: Rusibra Hull Width & Overall Beam
# Снапшот №8: Ширина корпуса и общий габарит Rusibra

## EN: Overall Dimensions
- **Overall Beam (Bmax_total):** 6.7 meters (Working standard).
- **Distance between Hull Centers:** ~5.3 meters.
- **Clear Span (Bridge Deck):** ~3.9 meters between inner hull sides.
- **Status:** Approved for stability and VVP (Inland Waterways) lock compatibility.

## RU: Общие размерения
- **Габаритная ширина (Bmax_total):** 6.7 метра (Рабочий стандарт).
- **Расстояние между осями поплавков:** ~5.3 метра.
- **Чистый пролет (Мост):** ~3.9 метра между внутренними бортами поплавков.
- **Статус:** Согласовано исходя из требований остойчивости и габаритов шлюзов ВВП.

## EN: Single Hull Width Logic
- **Waterline Width:** 1.1 m.
- **Max Width with Flare:** 1.4 m.
- **Note:** The 6.7m overall beam allows for optimal righting moment for a 11.8m vessel.

## RU: Логика ширины корпуса
- **Ширина по ватерлинии:** 1.1 м.
- **Макс. ширина с «губой»:** 1.4 м.
- **Примечание:** Общий габарит 6.7 м обеспечивает оптимальный восстанавливающий момент для судна длиной 11.8 м.

# Snapshot #10: Bow Structure & Longitudinal Stringer
# Снапшот №10: Носовая структура и продольный стрингер

## EN: Bow Section Configuration
- **Longitudinal Stringer:** A central beam connecting Beam #1 and Beam #2.
- **Trampoline Setup:** Dual-net configuration. Nets are stretched between the hulls and the central stringer (not hull-to-hull).
- **Function:** Stabilizes the bow against forestay tension and provides a rigid mounting point for anchoring systems.

## RU: Конфигурация носовой секции
- **Продольный стрингер:** Центральная балка, соединяющая Балку №1 и Балку №2.
- **Устройство батута:** Двухсеточная конфигурация. Сетки натягиваются между поплавками и центральным стрингером (а не от поплавка до поплавка).
- **Функция:** Стабилизирует нос против натяжения форштага и обеспечивает жесткую точку крепления для якорных систем.

# Snapshot #11: Interior Heights & Bridge Recess
# Снапшот №11: Внутренняя высота и заглубление моста

## EN: Ergonomics & Height Strategy
- **Target Height:** 1.8 m in all living areas (hulls and cabin).
- **Hull Solution:** 20 cm lightweight sandwich superstructures on top of the pontoons to house upper sections of bulkheads and beam attachments.
- **Cabin Solution:** Central floor recess (20 cm deep, 1.2-2.0 m wide) between the main beams. This allows for standing headroom without increasing total vessel height/windage.

## RU: Энергономика и стратегия высоты
- **Целевая высота:** 1.8 м во всех жилых зонах (поплавки и рубка).
- **Решение для поплавков:** Легкие сэндвич-надстройки высотой 20 см над палубой поплавков для размещения верхних частей шпангоутов и узлов крепления балок.
- **Решение для рубки:** Центральное заглубление пола («корыто») глубиной 20 см и шириной 1.2–2.0 м между основными балками. Это позволяет стоять в полный рост без увеличения общей высоты и парусности судна.

## EN: Hydrodynamic Considerations
- **Bridge Recess Safety:** The bottom of the recessed floor must be shaped to deflect waves (skid-like profile) to prevent heavy slamming.
- **Trim & Balance:** Due to the 0.75m bow rocker rise, weight distribution (especially the mast on Beam #4) must be carefully calculated to avoid "nose-diving" in static trim.

## RU: Гидродинамические аспекты
- **Безопасность заглубления:** Дно заглубленной части пола должно иметь обтекаемую форму («лыжа») для отражения ударов встречной волны (слемминга).
- **Дифферент и баланс:** Из-за подъема рокера в носу на 0.75 м, распределение веса (особенно мачты на балке №4) требует точного расчета, чтобы избежать дифферента на нос в статике.

# Snapshot #12 (FINAL): Rusibra Confirmed Hull & Balance
# Снапшот №12 (ФИНАЛЬНЫЙ): Утвержденная геометрия и баланс Rusibra

## EN: Final Rocker Profile
- **Bow Rise:** 0.65 m (Optimized for wave-piercing + forward mast support).
- **Stern Rise:** 0.55 m (Optimized for flow release and rudder protection).
- **Keelson Taper:** 40 cm (Center) -> 20 cm (Stern) -> 10 cm (Bow).

## RU: Финальный профиль рокера
- **Подъем носа:** 0.65 м (Оптимизировано для прорезания волны и поддержки передней мачты).
- **Подъем кормы:** 0.55 м (Оптимизировано для схода потока и защиты руля).
- **Сужение кильсона:** 40 см (Центр) -> 20 см (Корма) -> 10 см (Нос).

## EN: Center of Effort & Positioning
- **Mast Position:** Forward-biased (Beam #4), balanced by a long 3.5m aft-set keel.
- **Structural Integrity:** Mast compression is supported by the widest 40cm keelson section and the 0.65m buoyancy reserve in the bow.

## RU: Центр парусности и позиционирование
- **Позиция мачты:** Смещена вперед (Балка №4), сбалансирована длинным 3.5-метровым килем, смещенным в корму.
- **Конструктивная прочность:** Нагрузка от мачты опирается на самую широкую (40 см) часть кильсона и поддерживается запасом плавучести в 0.65 м в носовой части.

# Snapshot #14: Structural Logic Comparison (Wharram vs Rusibra)
# Снапшот №14: Сравнение силовой логики (Wharram vs Rusibra)

## EN: Structural Philosophy
- **Wharram Style:** Uses two beams + bridge deck to compensate for flexible (lashed) hull connections.
- **Rusibra Style:** Uses a single heavy-duty "Master Beam" (#4) integrated into a rigid 6-beam grid.
- **Load Distribution:** Mast compression on Beam #4 is shared with Beams #3 and #5 via the rigid cabin floor and longitudinal stringers.

## RU: Силовая философия
- **Стиль Wharram:** Использует две балки + платформу для компенсации гибких (веревочных) соединений корпусов.
- **Стиль Rusibra:** Использует одну сверхмощную «Мачтовую балку» (№4), интегрированную в жесткую сетку из 6 балок.
- **Распределение нагрузки:** Давление мачты на балку №4 распределяется на балки №3 и №5 через жесткий пол рубки и продольные стрингеры.

# Snapshot #15: Rusibra Unified Design & Structural Specs (Current Session)
# Снапшот №15: Унифицированный дизайн и характеристики Rusibra (Итоги сессии)

## EN: 1. Hull Geometry & Balance (Revised)
- **LOA:** 11.8 m.
- **Beam (Individual Hull):** 1.1 m (WL) / 1.4 m (Max with flare).
- **Overall Beam:** 6.7 m (Working standard).
- **Rocker Profile:** Asymmetrical balance for forward mast support.
  - Bow Rise: 0.65 m (optimized for wave-piercing & buoyancy).
  - Stern Rise: 0.55 m (optimized for flow release).
- **Keelson Taper:** 40 cm (Center) -> 20 cm (Stern) -> 10 cm (Bow).
- **Mast Position:** Forward-biased (Beam #4), balanced by a 3.5m aft-set keel and rudder at 10.95m.

## RU: 1. Геометрия корпуса и баланс (Пересмотрено)
- **Общая длина (LOA):** 11.8 м.
- **Ширина (Один поплавок):** 1.1 м (ВЛ) / 1.4 м (Макс. с «губой»).
- **Габаритная ширина:** 6.7 м (Рабочий стандарт).
- **Профиль рокера:** Асимметричный баланс под переднюю мачту.
  - Подъем носа: 0.65 м (оптимизация под wave-piercing и плавучесть).
  - Подъем кормы: 0.55 м (оптимизация под сход потока).
- **Сужение кильсона:** 40 см (Центр) -> 20 см (Корма) -> 10 см (Нос).
- **Позиция мачты:** Смещена вперед (Балка №4), сбалансирована 3.5-метровым кормовым килем и рулем на 10.95 м.

## EN: 2. Bridge Structure & Beams
- **Six-Beam Layout:** Modular system for assembly/disassembly.
  - Beam #4 (Mast): Heaviest load, integrated into cabin interior (furniture base). Height 250-300mm.
  - Beams #1, #2, #3, #5, #6: Functional spacing for trampoline, cabin walls, and cockpit.
- **Construction:** Box-section (plywood + internal ribs + solid timber inserts at ends).
- **Longitudinal Stringer:** Connects Beams #1 & #2 in the bow for forestay and anchor support.

## RU: 2. Структура моста и балки
- **Схема из 6 балок:** Модульная система для сборки/разборки.
  - Балка №4 (Мачтовая): Макс. нагрузка, интегрирована в интерьер рубки (основание мебели). Высота 250-300 мм.
  - Балки №1, №2, №3, №5, №6: Функциональное зонирование (батут, стенки рубки, кокпит).
- **Конструктив:** Коробчатое сечение (фанера + ребра + брус в торцах).
- **Продольный стрингер:** Соединяет балки №1 и №2 в носу для поддержки форштага и якоря.

## EN: 3. Deck & Superstructures
- **Hull Superstructure:** Raised by 20 cm above pontoons (lightweight sandwich).
- **Walkways:** 40 cm wide side decks (potopchina) outside the superstructure for safe movement.
- **Cabin Floor:** Recessed central zone ("the tray") 20 cm deep between beams for 1.8 m interior height.
- **Roof Construction:** 6 mm plywood (top) + 30 mm insulation (bottom) + internal fiberglass layer. Sealed with epoxy and supported by wooden battens (beams).

## RU: 3. Палуба и надстройки
- **Надстройка поплавков:** Поднята на 20 см (легкий сэндвич).
- **Проходы:** Потопчины шириной 40 см по бортам снаружи надстроек.
- **Пол рубки:** Центральное заглубление («корыто») на 20 см между балками для обеспечения высоты 1.8 м.
- **Конструкция крыши:** Фанера 6 мм (верх) + 30 мм утеплитель (низ) + внутренний слой стеклоткани. Консервация эпоксидной смолой, опора на бимсы (рейки).

## EN: 4. Assembly/Disassembly Protocols
- **Connection:** Double frame (bulkhead) system at beam attachment points.
- **Fastening:** M20 studs with epoxy-sealed nuts (designed to be cut for transport).

## RU: 4. Протоколы сборки/разборки
- **Соединение:** Система двойных шпангоутов в местах крепления балок.
- **Крепеж:** Шпильки M20, гайки загерметизированы эпоксидкой (рассчитаны на срезание при демонтаже).

# Snapshot #16: Composite Fastening System (Metal-Free)
# Снапшот №16: Композитная система крепежа (Безметалловая)

## EN: Fastening Hardware
- **Studs:** Fiberglass (GFRP) or Basalt (BFRP) threaded rods. M20 diameter.
- **Washers:** Thick G10 / FR4 composite plates or Textolite (structural laminate).
- **Locking Method:** Composite nuts or sleeves, sealed with epoxy-saturated fiberglass "cocoons".
- **Disassembly:** Sacrificial design; the outer epoxy/glass head is cut off to release the beam.

## RU: Крепежные элементы
- **Шпильки:** Стеклопластиковый (GFRP) или базальтопластиковый (BFRP) резьбовой стержень. Диаметр М20.
- **Шайбы:** Толстые пластины из композита G10 / FR4 или текстолита (конструкционный ламинат).
- **Метод фиксации:** Композитные гайки или втулки, запечатанные «коконами» из стеклоткани, пропитанной эпоксидной смолой.
- **Демонтаж:** Жертвенная конструкция; внешний эпоксидно-стеклянный узел срезается для освобождения балки.

## EN: Configuration per Joint
- 4 Vertical studs (compression/uplift).
- 4 Horizontal studs (torsion/shear).
- Total: 8 composite studs per beam end.

## RU: Конфигурация на один узел
- 4 вертикальных шпильки (сжатие/отрыв).
- 4 горизонтальных шпильки (кручение/сдвиг).
- Итого: 8 композитных шпилек на один конец балки.

# Snapshot #17: Composite Stud Engineering & Mount Detail
# Снапшот №17: Инженерия композитных шпилек и узла крепления

## EN: Hardware Selection
- **Material:** High-temperature dielectric fiberglass threaded rod (GFRP), M20.
- **Nut System:** Custom-made from structural textolite (STEF) rods or thick plates.
- **Sealing:** All composite fasteners to be epoxy-bonded and overwrapped with fiberglass tape for permanent locking.

## RU: Выбор крепежа
- **Материал:** Высокотемпературная диэлектрическая стеклопластиковая шпилька (GFRP), М20.
- **Система гаек:** Самодельные гайки/втулки из конструкционного текстолита (СТЭФ).
- **Фиксация:** Весь композитный крепеж вклеивается на эпоксидную смолу и бронируется снаружи лентой стеклоткани для «мертвой» фиксации.

## EN: Mounting Node Geometry
- **Isolation:** 3-5mm industrial rubber (TMKSh) or polyurethane gaskets between the beam and the frame on all contact surfaces (horizontal and vertical).
- **Reinforcement:** A "Saddle" (solid 100mm+ filler block) between double bulkheads to support the beam from below.
- **Load Paths:** Vertical studs for lift/compression; Horizontal studs for torsion/shear.

## RU: Геометрия узла крепления
- **Изоляция:** Прокладки из техпластины (ТМКЩ) или полиуретана 3-5 мм на всех плоскостях контакта балки и шпангоутов (горизонтальных и вертикальных).
- **Усиление:** «Седло» (закладной блок 100+ мм) между двойными шпангоутами для опоры балки снизу.
- **Распределение нагрузок:** Вертикальные шпильки — на отрыв/сжатие; горизонтальные — на кручение/сдвиг.

# Snapshot #18: Finalized Ocean-Ready Hull Geometry (Revision 2024)
# Снапшот №18: Утвержденная океанская геометрия корпуса (Ревизия 2024)

## EN: Vertical Hull Profile (Ref Point: 0.0 at Keelson Bottom)
- **Waterline (WL):** 0.75 m.
- **Bridge Clearance:** 1.65 m from bottom (0.9 m from WL).
- **Cabin Floor (Recess):** 1.4 m from bottom (0.65 m from WL).
- **Total Hull Height (to deck):** 1.65 m (+ 20 cm superstructure = 1.85 m interior).

## RU: Вертикальный профиль корпуса (Точка отсчета: 0.0 — низ кильсона)
- **Ватерлиния (WL):** 0.75 м.
- **Клиренс (просвет под мостом):** 1.65 м от дна (0.9 м от WL).
- **Пол рубки (корыто):** 1.4 м от дна (0.65 м от WL).
- **Полная высота поплавка (до палубы):** 1.65 м (+ 20 см надстройка = 1.85 м внутри).

## EN: Finalized Rocker Table (Step 0.9 m / 1.0 m)
- **0.0 m (Bow):** 0.550 m (Sharp entry, 20cm below WL).
- **0.9 m:** 0.365 m.
- **1.9 m:** 0.205 m.
- **2.9 m:** 0.090 m.
- **3.9 m:** 0.025 m.
- **4.9 m - 8.9 m:** 0.000 m (**4-meter FLAT SECTION / THE SKI**).
- **9.9 m:** 0.075 m.
- **10.9 m:** 0.310 m (Rudder stock area).
- **11.8 m (Stern):** 0.650 m (Flow release, 10cm below WL).

## RU: Финальная таблица рокера (Шаг 0.9 м / 1.0 м)
- **0.0 м (Нос):** 0.550 м (Острый вход, 20 см под WL).
- **0.9 м:** 0.365 м.
- **1.9 м:** 0.205 м.
- **2.9 м:** 0.090 м.
- **3.9 м:** 0.025 м.
- **4.9 м – 8.9 м:** 0.000 м (**4-метровая ПЛОСКАЯ ЛЫЖА**).
- **9.9 м:** 0.075 м.
- **10.9 м:** 0.310 м (Зона баллера руля).
- **11.8 м (Корма):** 0.650 м (Сход потока, 10 см под WL).

## EN: Engineering Rationale
- **Stability:** The 4m flat section prevents hobby-horsing (pitching) in the ocean.
- **Buoyancy:** Shifted aft to support engine/cockpit weight and forward-stepped mast.
- **Hydrodynamics:** High-set stern (0.65m) minimizes drag; deep-set bow (0.55m) improves wave-piercing.

## RU: Инженерное обоснование
- **Стабильность:** 4-метровая «лыжа» предотвращает дельфинирование в океане.
- **Плавучесть:** Смещена в корму для поддержки веса двигателей и смещенной вперед мачты.
- **Гидродинамика:** Высокая корма (0.65 м) минимизирует сопротивление; заниженный нос (0.55 м) улучшает прорезание волны.

# Snapshot #19: Mast Section Framing & Beam Layout (Part 1)
# Снапшот №19: Силовой набор мачтовой секции и расстановка балок (часть 1)

## EN: Structural Beam Layout (0.0 to 5.7 m)
- **Beam #1 (Bow):** 0.50 m. Frame #1 (0.50m), Frame #2 (0.65m). Primary forestay attachment.
- **Beam #2 (Foredeck):** 2.65 m. Frame #3 (2.65m), Frame #4 (2.80m). Boundary of the trampoline.
- **Beam #3 (Cabin Front):** 4.00 m. Frame #5 (4.00m), Frame #6 (4.15m). Start of the hard enclosure.
- **Beam #4 (Mast):** 5.50 m. Frame #7 (5.50m), Frame #8 (5.70m). Central load axis.

## RU: Расстановка силовых балок (от 0.0 до 5.7 м)
- **Балка №1 (Нос):** 0.50 м. Шпангоут №1 (0.50м), Шпангоут №2 (0.65м). Крепление форштага.
- **Балка №2 (Передняя палуба):** 2.65 м. Шпангоут №3 (2.65м), Шпангоут №4 (2.80м). Граница батута.
- **Балка №3 (Перед стенкой рубки):** 4.00 м. Шпангоут №5 (4.00м), Шпангоут №6 (4.15м). Начало закрытой рубки.
- **Балка №4 (Мачтовая):** 5.50 м. Шпангоут №7 (5.50м), Шпангоут №8 (5.70м). Главная силовая ось.

## EN: Frame Integrity (The "Collar" reinforcement)
- **Frames #7 & #8:** Passage frames under the mast.
- **Reinforcement:** Double-sided plywood overlays (100-150mm wide) around the passage.
- **Lamination:** Heavy biaxial fiberglass wrap (3-4 layers) around the opening.
- **Vertical Support:** Hardwood pillars (40x40mm) to transfer mast compression to the keelson.

## RU: Целостность шпангоутов (Усиление «Воротник»)
- **Шпангоуты №7 и №8:** Проходные шпангоуты под мачтой.
- **Усиление:** Двусторонние фанерные накладки (кницы) шириной 100-150 мм по периметру прохода.
- **Ламинирование:** 3-4 слоя биаксиальной стеклоткани через торцы прохода.
- **Вертикальные опоры:** Пиллерсы из твердых пород дерева (40х40 мм) для передачи компрессии мачты на кильсон.

# Snapshot #20: Full Structural Grid & Frame Assignment
# Снапшот №20: Полная силовая сетка и распределение шпангоутов

## EN: Complete Beam & Frame Positioning (0.0 - 11.8 m)
1. **Bow Section (Crash Box):** 
   - 0.0m - 0.50m: Sealed buoyancy/foam zone.
2. **Beam #1 (Forepeak):** 0.50m - 0.65m. 
   - **Frames #1 & #2:** Integrated bow stiffness, forestay attachment.
3. **Trampoline Zone:** 2.0m open net between Beam #1 and #2.
4. **Beam #2 (Deck Start):** 2.65m - 2.80m. 
   - **Frame #3 (2.65m):** Passage to lockers. 
   - **Frame #4 (2.80m):** **WATERTIGHT BULKHEAD.** Safety barrier.
5. **Open Hard Deck:** 1.2m solid walkway between Beam #2 and #3.
6. **Beam #3 (Cabin Front):** 4.00m - 4.15m. 
   - **Frame #5 (4.00m):** **WATERTIGHT BULKHEAD.** Living module start.
7. **Beam #4 (Mast Axis):** 5.50m - 5.70m. 
   - **Frames #7 & #8:** Passage frames with "Collar" reinforcement & pillars.
8. **Beam #5 (Cabin Rear):** 8.00m - 8.15m. 
   - **Frame #9:** Main entrance bulkhead. End of 4m cabin.
9. **Cockpit Zone:** 2.35m clear length between Beam #5 and #6.
10. **Beam #6 (Stern):** 10.50m - 10.65m. 
    - **Frame #10:** Protection for rudder stocks (located at 10.95m).

## RU: Полное позиционирование балок и шпангоутов (0.0 - 11.8 м)
1. **Носовая секция (Краш-бокс):** 
   - 0.0м - 0.50м: Герметичный отсек / зона заполнения пеной.
2. **Балка №1 (Форпик):** 0.50м - 0.65м. 
   - **Шпангоуты №1 и №2:** Жесткость носа, точка крепления форштага.
3. **Зона батута:** 2.0м открытой сетки между балками №1 и №2.
4. **Балка №2 (Начало палубы):** 2.65м - 2.80м. 
   - **Шпангоут №3 (2.65м):** Проходной в хозблок/каюту.
   - **Шпангоут №4 (2.80м):** **ГЕРМЕТИЧНАЯ ПЕРЕБОРКА.** Барьер безопасности.
5. **Открытая палуба:** 1.2м жесткого настила между балками №2 и №3.
6. **Балка №3 (Передняя стенка рубки):** 4.00м - 4.15м. 
   - **Шпангоут №5 (4.00м):** **ГЕРМЕТИЧНАЯ ПЕРЕБОРКА.** Начало жилого модуля.
7. **Балка №4 (Мачтовая ось):** 5.50м - 5.70м. 
   - **Шпангоуты №7 и №8:** Проходные с «воротниковым» усилением и пиллерсами.
8. **Балка №5 (Задняя стенка рубки):** 8.00м - 8.15м. 
   - **Шпангоут №9:** Основная переборка входа. Конец 4-метровой рубки.
9. **Зона кокпита:** 2.35м чистой длины между балками №5 и №6.
10. **Балка №6 (Кормовая):** 10.50м - 10.65м. 
    - **Шпангоут №10:** Защита баллеров рулей (баллеры на 10.95м).

## EN: System Integrity
- **Watertight Zones:** 3 main compartments per hull (Bow, Main Living, Stern Tech).
- **Beam-Frame Link:** All beams mounted via composite M20 studs into double-frame saddles with rubber vibration damping.

## RU: Целостность системы
- **Герметичные зоны:** 3 основных отсека на поплавок (Носовой, Жилой, Кормовой тех.отсек).
- **Связь Балка-Шпангоут:** Все балки монтируются через композитные шпильки М20 в «седла» двойных шпангоутов с резиновой виброизоляцией.

# Snapshot #21: Full Frame Schedule (The Skeleton)
# Снапшот №21: Полный график шпангоутов (Скелет корпуса)

## EN: Frame Distribution (0.0 to 11.8 m)
- **0.0 m:** Bow (Entry point).
- **0.50 m / 0.65 m:** Beam #1 Supports (Forestay node).
- **1.30 m / 2.00 m:** Intermediate frames (Trampoline zone).
- **2.65 m / 2.80 m (W):** Beam #2 Supports (Watertight barrier).
- **3.40 m:** Intermediate frame (Open deck).
- **4.00 m (W) / 4.15 m:** Beam #3 Supports (Cabin front bulkhead).
- **4.80 m:** Intermediate frame (Living zone).
- **5.50 m / 5.70 m:** Beam #4 Supports (Mast axis, reinforced "Collar").
- **6.40 m / 7.20 m:** Intermediate frames (Central salon).
- **8.00 m (W) / 8.15 m:** Beam #5 Supports (Cabin rear/Cockpit start).
- **8.90 m / 9.70 m:** Intermediate frames (Cockpit/Aft lift).
- **10.50 m / 10.65 m:** Beam #6 Supports (Rudder protection).
- **11.20 m:** Intermediate frame (Stern steps).
- **11.80 m:** Transom.

## RU: Распределение шпангоутов (от 0.0 до 11.8 м)
- **0.0 м:** Форштевень.
- **0.50 м / 0.65 м:** Опоры Балки №1 (Узел форштага).
- **1.30 м / 2.00 м:** Промежуточные шпангоуты (Зона батута).
- **2.65 м / 2.80 м (Г):** Опоры Балки №2 (Герметичная переборка).
- **3.40 м:** Промежуточный шпангоут (Открытая палуба).
- **4.00 м (Г) / 4.15 м:** Опоры Балки №3 (Передняя стенка рубки).
- **4.80 м:** Промежуточный шпангоут (Жилая зона).
- **5.50 м / 5.70 м:** Опоры Балки №4 (Мачтовая ось, усиленный «Воротник»).
- **6.40 м / 7.20 м:** Промежуточные шпангоуты (Центральный салон).
- **8.00 м (Г) / 8.15 м:** Опоры Балки №5 (Выход из рубки/Начало кокпита).
- **8.90 м / 9.70 м:** Промежуточные шпангоуты (Кокпит/Подъем кормы).
- **10.50 м / 10.65 м:** Опоры Балки №6 (Защита рулей).
- **11.20 м:** Промежуточный шпангоут (Ступеньки в корме).
- **11.80 м:** Транец.

## EN: Construction Notes
- **Thickness:** 15-18mm plywood for load-bearing (beam) frames; 10-12mm for intermediates.
- **Joints:** 40x60mm interlocking notch for the keelson.
- **Access:** Watertight bulkheads marked (W/Г) ensure buoyancy compartments.

## RU: Конструктивные примечания
- **Толщина:** Фанера 15-18 мм для силовых шпангоутов; 10-12 мм для промежуточных.
- **Соединение:** Паз 40х60 мм для врезки в кильсон «в замок».
- **Доступ:** Герметичные переборки (Г) формируют отсеки непотопляемости.

# Snapshot #23: Composite Stem-Breasthook Design
# Снапшот №23: Конструкция композитного форштевня-брештука

## EN: Stem-Breasthook Construction
- **Material:** Double layer of 9mm plywood (18mm total thickness).
- **Position:** Vertically aligned, running from the stem point (0.0m) to the first structural bulkhead (Frame #1 at 0.50m).
- **Function:** Direct load transfer from the bow impact zone to the main structural Beam #1. Provides a rigid guide for hull lamination.

## RU: Конструкция форштевня-брештука
- **Материал:** Двойной слой 9-мм фанеры (суммарно 18 мм).
- **Расположение:** Вертикально по оси, от точки форштевня (0.0 м) до первого силового шпангоута (0.50 м).
- **Функция:** Прямая передача нагрузок от зоны удара в носу на основную силовую Балку №1. Служит жесткой направляющей для ламинирования обшивки.

## EN: Updated Hull Thickness (Optimization)
- **Bottom/Keel area:** 12-15 mm (reduced from 18mm for weight saving).
- **Sides (Above WL):** 9 mm (standard for speed and flex).
- **Lamination:** 3-4 layers of fiberglass below WL, 2 layers above.

## RU: Обновленные толщины корпуса (Оптимизация)
- **Днище/Район киля:** 12-15 мм (снижено с 18 мм для экономии веса).
- **Борта (выше ВЛ):** 9 мм (стандарт для скорости и гибкости).
- **Ламинирование:** 3-4 слоя стеклоткани ниже ВЛ, 2 слоя выше ВЛ.

# Snapshot #25: Double-Deck Bridge System (The Truss Concept)
# Снапшот №25: Двухуровневая система моста (Концепция фермы)

## EN: Double-Deck Structural Philosophy
- **Level 1 (Structural):** Main beams at 1.95m from baseline. Heavy-duty construction, 8-stud mounting. Handles primary torsion and rigging loads.
- **Level 2 (Living/Floor):** Secondary beams at 1.45m from baseline (0.7m above WL). 1-stud mounting per end. Acts as floor support and lateral brace.
- **Synergy:** The two levels, connected by cabin walls, form a massive box truss, significantly increasing overall vessel rigidity.

## RU: Двухуровневая силовая схема моста
- **Уровень 1 (Силовой):** Основные балки на отметке 1.95 м от ОЛ. Сверхмощная конструкция, крепление на 8 шпилек. Несут основные нагрузки на кручение и такелаж.
- **Уровень 2 (Палубный/Пол):** Вспомогательные балки на отметке 1.45 м от ОЛ (0.7 м над WL). Крепление на 1 шпильку с каждой стороны. Опора для пола и распорка бортов.
- **Синергия:** Оба уровня, связанные стенками рубки, образуют мощную пространственную ферму, радикально повышая жесткость судна.

## EN: Construction Notes
- **Floor Deck:** Sandwich (3mm plywood / 20mm foam / 3mm plywood) mounted under the secondary beams.
- **Storage:** Voids between the floor and the main beams (0.5m height) used as technical lockers and storage.

## RU: Конструктивные примечания
- **Настил пола:** Сэндвич (3 мм фанера / 20 мм пенопласт / 3 мм фанера), подшит снизу к вспомогательным балкам.
- **Хранение:** Пространство между полом и основными балками (высотой 0.5 м) используется как технические рундуки и склады.
