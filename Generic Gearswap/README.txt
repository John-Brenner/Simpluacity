## How to use
- Find the gearset you want to edit(e.g. 'sets.precast.FC')
- Insert gear names inside the quotes with the name displayed in-menu('Aya. Cosciales +2')
- You do NOT need to understand GearSwap flow to use this file

## GearSwap flow
When you can a spell or use an ability, generally GearSwap will swap in this order:
- idle/engaged(whichever you're in) -> precast -> midcast -> back to idle/engaged

    **Precast:** Swapped to before the action starts (Fast Cast and Enmity are checked here)
    **Midcast:** Swapped to as the action starts (Basically everything that's not Fast Cast and Enmity are checked here)
    **Idle:** Swapped to after midcast, zoning, or exiting combat
    **Engaged:** Swapped to when you have your weapon drawn

Example White Mage Fast Cast Set:

sets.precast.FC = {
    main="Sucellus",
    sub="Chanter's Shield",
    ammo="Impatiens",
    head="Ebers Cap +2",
    body="Inyanga Jubbah +2",
    hands={ name="Fanatic Gloves", augments={'MP+50','Healing magic skill +10','"Conserve MP"+7','"Fast Cast"+7',}},
    legs="Aya. Cosciales +2",
    feet="Regal Pumps +1",
    neck="Orunmila's Torque",
    ear1="Loquac. Earring",
    ear2="Malignance Earring",
    ring1="Kishar ring",
    ring2="Weather. ring",
    back={ name="Alaunus's Cape", augments={'MND+20','Mag. Acc+20 /Mag. Dmg.+20','"Fast Cast"+10','Damage taken-5%',}},
    waist="Witful Belt",
    }