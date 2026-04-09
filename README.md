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
