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
