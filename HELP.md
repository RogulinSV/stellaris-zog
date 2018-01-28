https://www.reddit.com/r/Stellaris/comments/4jjhj3/lists_of_effects_modifiers_scopes_and_triggers/
---------------------------------------------------------------

###############################
# Modifiers
###############################
icon = "gfx/interface/icons/planet_modifiers/pm_dangerous_wildlife.dds"
icon_frame = 2
    
###############################
# Ship Features
###############################
Special effects such as fire-rate reduction, ftl slowdown, etc are applied via component_templates, under 00_utilites_auras

These can apply a hostile aura that applies an effect on nearby fleets.

###############################
# Technology Features
###############################
Most buildings/ship parts/policies/edicts/etc are unlocked via checking for the technology code name.

Unlocked via feature_flags = { } in technology files:

colony_ship_rushed - Unlocks Colony Ships?
build_terraform_station - Unlocks Terraforming
uplifting - Unlocks Uplifting mechanic
modify_traits - Unlocks Trait modification
pop_self_modification - Unlocks Pop modification
hyperlanes - Unlocks Hyper Lanes

Special modifiers unlocked through tech codename directly:

tech_xeno_relations - Unlocks Alliances
tech_xeno_supremacy - Unlocks Vassals
tech_xeno_diplomacy - Unlocks Federations
tech_xeno_integration - Unlocks Other Species leaders
tech_manifest_destiny - Unlocks reduced influence-cost of wargoals
tech_ethical_equations - Unlocks Slavery
assist_research - Unlocks Assist Research (science ships can boost research output of planet)
tech_hyperlane_mapping - Shows Hyper Lanes?

FTL Drives:
tech_wormhole_generation_1 - Unlocks Wormhole ship modules
tech_warp_drive_1 - Unlocks Warp Drives
tech_jump_drive_1 - Unlocks Jump Drives

###############################
# Country
###############################
max_rivalries = 3
max_embassies = 3

all_technology_research_speed = 0.10
influence_gain_mult = -0.1
influence_gain_add = 3

alliance_influence_cost = 1
rivalry_influence_gain = 0.5
        
country_leader_cap = 1
country_leader_pool_size = 1
country_trade_attractiveness = 0.10
country_core_sector_planet_cap = 2
country_resettlement_cost_mult = -0.15
country_ship_upgrade_cost_mult = -0.15
country_sector_cap_add = 1
country_border_mult = 0.2
country_trust_growth = 0.10

country_engineering_tech_research_speed = 0.3
country_society_tech_research_speed = -0.10
country_physics_tech_research_speed = -0.10
        
category_biology_research_speed_mult = 0.1
category_statecraft_research_speed_mult = 0.1
category_industry_research_speed_mult = 0.1
category_materials_research_speed_mult = 0.1
category_rocketry_research_speed_mult = 0.1
category_voidcraft_research_speed_mult = 0.1
category_field_manipulation_research_speed_mult = 0.1
category_particles_research_speed_mult = 0.1
category_computing_research_speed_mult = 0.1
category_psionics_research_speed_mult = 0.1
category_new_worlds_research_speed_mult = 0.1
category_military_theory_research_speed_mult = 0.1

science_ship_survey_speed  = 0.20
ship_anomaly_research_speed_mult = 0.20
ship_anomaly_generation_chance_mult = 0.10
ship_anomaly_fail_risk = -0.10
ship_anomaly_research_speed_mult = 0.35

leader_age = 50
leader_influence_cost = 0.20
leader_skill_levels = 1

# Test for dynamic setup
vultaum_asteroid_category_research_speed_mult = 0.5
vultaum_asteroid_category_research_fail_risk_add = -0.25
vultaum_gasgiant_category_research_speed_mult = 0.5
vultaum_gasgiant_category_research_fail_risk_add = -0.25

trait_points = 1

max_minerals = 1500
max_energy = 250

num_tech_alternatives_add = 1

edict_influence_cost = -0.25
edict_length_mult = 0.25

species_leader_exp_gain = 0.25

building_time_mult = -0.05
megastructure_build_speed_mult = 0.2
terraform_speed_mult = 0.2
terraforming_cost_mult = -0.2

faction_influence_add = 1
 
###############################
# Construction
###############################
# These modifiers may be created dynamically to the ship classes created. Test this.

shipsize_military_station_small_build_cost_mult = -0.15
shipsize_military_station_medium_build_cost_mult = -0.15
shipsize_military_station_large_build_cost_mult = -0.15

shipsize_military_station_small_upkeep_mult = -0.2
shipsize_military_station_medium_upkeep_mult = -0.2
shipsize_military_station_large_upkeep_mult = -0.2

shipsize_constructor_build_cost_mult = -0.15

shipsize_mining_station_build_cost_mult = -0.15

shipsize_colonizer_build_cost_mult = -0.35
shipsize_colonizer_construction_speed_mult

shipsize_terraform_station_build_cost_mult = -0.25

shipsize_orbital_station_build_cost_mult = -0.2

shipsize_outpost_station_build_cost_mult = -0.15

shipsize_corvette_build_cost_mult = -0.2
shipsize_corvette_construction_speed_mult = 0.25

shipsize_destroyer_build_cost_mult = -0.2
shipsize_destroyer_construction_speed_mult = 0.25

shipsize_cruiser_build_cost_mult = -0.2
shipsize_cruiser_construction_speed_mult = 0.25

shipsize_battleship_build_cost_mult = -0.2
shipsize_battleship_construction_speed_mult = 0.25

building_mining_network_1_build_cost_mult = -0.15
hydroponics_farm_build_cost_mult = -0.10
science_lab_build_cost_mult = -0.25

shipclass_military_station_build_cost_mult = -0.15
shipclass_military_station_hit_points_mult = 0.25
shipclass_military_station_damage_mult
shipclass_military_station_hit_points_mult = 0.1

# Test for dynamic setup
building_hydroponics_farm_1_build_cost_mult = -0.20

###############################
# Spaceport
###############################
spaceport_ship_build_cost_mult = -0.10
spaceport_ship_build_time_mult = -0.25

spaceport_module_cost_mult  = -0.1

###############################
# Planet
###############################
planet_ship_build_speed_mult = 0.20
planet_army_build_speed_mult = -0.33
planet_army_build_cost_mult = -0.15
planet_building_cost_mult = 0.15
planet_sensor_range_mult = 0.25
planet_migration_all_pull = 1
planet_migration_xeno_pull = 1
planet_border_mult = 1.0
planet_clear_blocker_time_mult = -0.06
planet_clear_blocker_cost_mult = -0.25
planet_colony_development_speed_mult = 0.25
planet_fortification_strength = 0.5

terraforming_cost_mult = -0.25

pc_desert_habitability = 0.1
pc_arid_habitability = 0.1
pc_tropical_habitability = 0.1
pc_continental_habitability = 0.1
pc_tundra_habitability = 0.1
pc_ocean_habitability = 0.1
pc_arctic_habitability = 0.1
pc_ai_habitability = 0.1
pc_nuked_habitability = 0.1
pc_gaia_habitability = 0.1
pc_ringworld_habitable_habitability = 0.1

###############################
# Army
###############################
army_health = 0.05
army_damage_mult = 0.05
army_upkeep_mult = -0.05
army_morale = 0.20

army_rank_increase = 1

army_defense_morale_mult = 0.2
army_defense_damage_mult = 0.2

army_attack_morale_mult = 0.2
army_attack_damage_mult = 0.2

army_morale_damage_mult = 0.15

###############################
# Fleet
###############################
fleet_emergency_ftl_min_days_mult = 1

ship_upkeep_mult = -0.10
ship_fire_rate_mult = 0.05
ship_armor_add = 10
ship_hitpoints_add = 1500
ship_weapon_damage = 0.15
ship_shield_hp_mult = -0.33
ship_evasion_mult = 0.05
ship_evasion_add = 5
ship_accuracy_add = 3
ship_combat_speed_mult = 0.2
ship_speed_mult = 0.15

ship_reparation_speed_mult = 0.15
ship_auto_repair_add = 0.02
ship_sensor_range_mult = 0.25
ship_hitpoints_mult = 0.2
ship_armor_mult = 0.10
ship_shield_regen_add_perc = 0.2

ship_ftl_wormhole_speed_mult = 0.25
ship_ftl_wormhole_range_mult = 0.5
ship_ftl_warp_range_mult = 0.5
ship_ftl_jumpdrive_range_mult = 0.50

ship_emergency_ftl_mult = -0.25
ship_interstellar_speed_mult = 0.20
ship_windup_mult = 4
ship_winddown_mult = -0.2


navy_size_add = 0.1
navy_size_mult = 1

damage_vs_country_type_amoeba_mult = 0.2
damage_vs_country_type_crystal_mult = 0.2
damage_vs_country_type_drone_mult = 0.1
damage_vs_country_type_cloud_mult = 0.1
damage_vs_country_type_swarm_mult = 0.2
damage_vs_country_type_ai_empire_mult = 0.1
damage_vs_country_type_extradimensional_mult = 0.20
damage_vs_country_type_extradimensional_2_mult = 0.20
damage_vs_country_type_extradimensional_3_mult = 0.20
damage_vs_country_type_fallen_empire_mult = 0.20
damage_vs_country_type_awakened_fallen_empire_mult = 0.20

weapon_type_energy_weapon_damage_mult = 0.10
weapon_type_energy_weapon_fire_rate_mult = 0.05

weapon_type_explosive_weapon_damage_mult = 0.10
weapon_type_explosive_weapon_fire_rate_mult = 0.05

weapon_type_kinetic_weapon_damage_mult = 0.10
weapon_type_kinetic_weapon_fire_rate_mult = 0.05

weapon_type_strike_craft_weapon_damage_mult = 0.05
weapon_type_strike_craft_weapon_fire_rate_mult = 0.05

###############################
# Pops
###############################
pop_other_species_happiness = 0.01
pop_environment_tolerance = -0.10
pop_slavery_tolerance = -0.1
pop_food_req_mult = -0.10
pop_growth_req_mult = -0.25
pop_ethic_shift = -0.20	
pop_happiness = -0.2
pop_robot_production_output = 0.2
pop_robot_build_cost_mult = 0.2
pop_xenophobia = 0.2
pop_alien_slavery_tolerance = 1.0
pop_migration_time = -0.5
pop_eff_wo_slaves = -0.1
pop_fortification_defense = 0.5
pop_resettlement_cost_mult = -0.1

slave_production_output = 0.2
slave_food_output = 0.2
        
pop_war_happiness = 0.05
pop_xenophobia = -0.2

garrison_health = 1.0

###############################
# Tile (applied to Planet)
###############################
tile_resource_minerals_mult = 1
tile_resource_food_mult = 0.20
tile_resource_energy_mult = 1

tile_resource_physics_research_mult = 1
tile_resource_society_research_mult = 1
tile_resource_engineering_research_mult = 1

---------------------------------------------------------------

###############################
# Scopes
###############################

THIS
ROOT
PREV
PREVPREV
PREVPREVPREV
PREVPREVPREVPREV
FROM
FROMFROM
OWNER
CONTROLLER
CAPITAL
RANDOM

event_target:NameHere

Core scopes can be extended with some specific scopes, like so: owner.capital_scope = { }

hidden: can be appended to scopes to hide them

hidden_effect = { }             # Effect not shown in tooltips
hidden_trigger = { }

NOT = { }
AND = { }
OR = { }

if = { limit = { }
    else = { }
    
    break = yes
}

random_list = {
    50 = { 
        modifier = {
            factor = 1
            
        }
    }
    50 = { }
}

random = {
    chance  = 50
}

###############################
# Scopeless Trigger
###############################
### Trigger ###
any_ship = { }              # any ship
any_system = { }            # any system trigger
any_rim_system = { ]
any_ship_in_system = { }
any_ambient_object = { }
any_member = { }            # Alliance
space_owner = { }
solar_system = { } 
owner = { }
owner_species = { }

last_created_ambient_object = { }
last_created_leader = { }
last_created_species = { }
last_created_fleet = { }
last_created_country = { }
last_created_pop = { }

###############################
# Scopeless Effect
###############################
closest_system = { }
random_country = { }
every_pop = { }
every_country = { }
every_ship = { }
every_planet = { }
random_system = { }
every_rim_system = { }
random_rim_system = { }
random_ambient_object = { }
every_ambient_object = { }
space_owner = { }
solar_system = { } 
owner = { }
owner_species = { }

###############################
# Cluster Effect
###############################
every_system_in_cluster = { }

###############################
# System Trigger
###############################
any_system_ambient_object = { }
any_neighbor_system = { }
any_planet = { }

###############################
# System Effect
###############################
every_system_planet = { }
random_planet = { }
random_system_planet = { }
random_system_ambient_object = { }
every_system_ambient_object = { }
every_fleet_in_system = { }
random_fleet_in_system = { }
every_neighbor_system = { }
random_neighbor_system = { }

###############################
# Country Trigger
###############################   
any_war = { }
any_attacker = { }
any_defender = { } 
any_country = { }       
any_owned_ship = { }        
any_neighbor_country = { }
any_system_within_border = { }
any_owned_leader = { }
any_owned_pop = { }
any_sector = { }
any_owned_fleet = { }
any_bordering_country = { }
any_neighbor_country = { }
capital_scope = { }
random_system = { }
any_war_defender = { }      
any_war_attacker = { }      
any_system_within_border = { }
any_planet_within_border = { }
any_owned_planet = { }
any_controlled_planet = { }

###############################
# Country Effect
###############################  
capital_scope = { }
every_owned_ship = { }
random_system = { }
random_owned_planet = { }
random_rim_system = { }
research_leader = { }
every_owned_planet = { }
every_controlled_planet = { }
random_controlled_planet = { }
every_war_defender = { }
every_war_attacker = { }
random_owned_ship = { }
every_owned_pop = { }
random_planet_within_border = { }
any_spaceport = { }
any_research_station = { }
any_mining_station = { }
random_system_within_border = { }
random_army_within_country = { }
every_planet_within_border = { }
every_army_within_country = { }
every_owned_leader = { }
random_owned_leader = { }
random_owned_pop = { }
random_sector = { }
every_sector = { }
random_owned_fleet = { }
random_neighbor_country = { }
every_pop_faction = { }
random_pop_faction = { }

###############################
# Planet Trigger
###############################
any_spaceport = { }             # any spaceport trigger
any_research_station = { }      # any research station outpost
any_mining_station = { }        # any mining station outpost
any_tile = { }
any_moon = { }
any_orbital_station = { }
orbital_deposit_tile = { }
orbit = { }
any_pop = { }

###############################
# Planet Effect
###############################
observation_outpost = { } 
observation_outpost_owner = { }
random_pop = { }
any_spaceport = { }
any_research_station = { }
any_mining_station = { }
random_research_station = { }
random_mining_station = { }
random_spaceport = { }
random_army = { }
every_tile = { }
random_tile = { }
random_moon = { }
every_moon = { }
every_planet_army = { }
random_owned_pop = { }
orbital_deposit_tile = { }
orbit = { }
every_owned_pop = { }
best_tile_for_pop = { }

###############################
# Fleet Trigger
###############################
fleet = { }

###############################
# Fleet Effect
###############################
random_owned_ship = { }

###############################
# Leader Trigger
###############################
leader = { }

###############################
# Tile Trigger
###############################
random_neighboring_tile = { limit = {} }
any_neighboring_tile = { }

###############################
# Tile Effect
###############################
every_neighboring_tile = { }
random_neighboring_tile = { }

###############################
# War Effect
###############################
random_war_defender = { }           # switches Scope to and picks a random defender in a war with a specified enemy
random_war_attacker = { }           # switches Scope to and picks a random attacker in a war with a specified enemy

---------------------------------------------------------------

###############################
# Effects
###############################
save_event_target_as = name             # save an event target
save_global_event_target_as = name      # save a global event target
clear_global_event_target = name        # clear a global event target
clear_global_event_targets = yes        # clear all global event targets

custom_tooltip = example_tooltip        # Add custom localisation tooltip

set_global_flag = example_flag          # Set global flag
remove_global_flag = example_flag       # Remove global flag

set_timed_global_flag                   # Sets a timed global flag
= { 
    flag = day_0 
    days = 7 
}

break                                   # break execution of effects
while                                   # repeats contained effects until limit fails or count is reached
= {
    limit = { }
}
switch                                  # Switches effect based on triggers
= {  
    trigger = ?
    ? = { }
    ? = { }
}


create_cluster = { ? }                  # creates a cluster centered around the specified spatial object
load_parameters = { ? }                 # Clears current parameters and loads new parameters from target

###############################
# Events
###############################
is_advisor_event = yes
is_triggered_only = yes
hide_window = yes
location = FROM
diplomatic = yes                    # Sets the event to be a diplomatic event between player and another country
option = { is_dialog_only = yes } 
auto_opens = yes
fire_only_once = yes

###############################
# Country
###############################
country_event = { id = example_event.1 days = 30 }  # fires a Country event
tooltip = "text"                                    # just a tooltip

abort_special_project = "name"              # Aborts a special research project for a country
add_physics_research = 100                  # Adds stored Physics research points to a county
add_society_research = 100                  # Adds stored Society research points to a county
add_engineering_research = 100              # Adds stored Engineering research points to a county
add_minerals = 500                          # Adds Minerals to a planet, tile or country
add_energy = -75                            # Adds a sum of energy to a country
add_influence = -100                        # Adds influence to a county
add_research_option = tech_fission_power    # Gives a specific tech to an empire and makes it always available for research.
add_ship_design = last_created_design       # Adds a ship design to a country!

create_fleet = { name = "Head-in-Sand" }    # Creates a new fleet
change_government = "divine_mandate"        # Change government in Empire.
country_add_ethic = "ethic_xenophobe"       # Adds an ethic to a country
country_remove_ethic = "ethic_xenophile"    # Removes an ethic from a country
create_sector = { ? }                       # Creates a sector
change_country_flag = "name"                # changes the flag of a country
change_dominant_species = "MAM"             # Changes the dominant species of the current Country

declare_war = ROOT                                      # Declare A War.
declare_white_peace_with = ROOT                         # Declare white peace with target country.

enable_faction_of_type = "faction"                      # orces a country to evaluate potential factions of a specific type right now. this would otherwise occur once a month
exile_leader_as = "name"                                # Exiles a leader and saves him associated to a custom name

establish_contact = ROOT                                # Country establishes contact with another country.
end_event_chain = "subterranean_civilization_chain"     # ends an event chain.
establish_communications_no_message = root.owner        # Establish communications between empires.
establish_communications = event_target:contact_empire  # Establish communications between empires.

give_technology = tech_terrestrial_sculpting            # Gives a specific tech to an empire.

leave_alliance = ROOT                                   # Leave any alliance/federation with country

set_country_flag = example_flag                         # Sets a flag on a country
set_tutorial_level = full                               # changes the tutorial level of a human of a country.
set_advisor_active = yes                                # activate or deactivate an advisor
set_faction_hostility = { set_hostile = yes }           # Sets hostility stance of a faction
set_primitive = yes                                     # Sets primitive status for a country
set_name = "name"                                       # Changes the name of a scope target
set_country_type = ROOT                                 # Changes country type
set_graphical_culture = "MAM"                           # Sets country graphical culture
set_heir = "name"                                       # Change the country heir.
set_aggro_range = 500                                   # Sets aggro range on a fleet or a country
set_leader = "name"                                     # Sets a leader from a previously exiled leader associated by a custom name
set_federation_leader = yes                             # Sets a country to lead a federation

remove_country_flag = example_flag                      # Removes a flag from a country
remove_relation_flag = example_flag                     # removes a relation flag.
remove_modifier = example_modifier
remove_point_of_interest = anomaly.4035.poi.1           # removed point of interest.
remove_opinion_modifier = "name"                        # Removes an opinion modifier to an empire.
remove_sector = ROOT                                    # Removes a sector.

add_threat                              # Adds threat
= {
    who = controller
    amount = 10 # scales to pops
}	

add_modifier                                # Gives a specific modifier to a planet.
= {
    modifier = "example_modifier"
    days = -1
}

create_military_fleet                       # Creates a military fleet with the designs of a specified country.
= {
    owner = this
    scaled_size = {
        base = 3
    }
}
        
set_variable                                # Sets a variable value
= { 
    which = var 
    value = 1 
}

set_relation_flag                           # sets a relation flag.
= {
    who = root
    flag = example_flag
}

set_timed_country_flag                      # Sets a timed flag on a country
= { 
    flag = day_0 
    days = 7 
}

add_event_chain_counter                     # adds amount to event chain counter.
= { 
    event_chain = "star_power_chain" 
    counter = "systems_visited_poi" 
    amount = 1 
}

begin_event_chain                           # begins an event chain.
= {
    event_chain = "star_power_chain"
    target = root
}

add_tech_progress                           # Gives progress to a specific technology
= {
    tech = tech_fission_power
    progress = 0.80
}
                
add_monthly_resource_mult                   # Adds multiple amount of monthly income of resource to country
= {
    resource = physics_research / engineering_research / society_research
    value = 60
    min = 2
    max = 5
}

add_war_demand                              # Adds a war demand to a rebel country
= {
    type = cede_planet
    parameter:planet = prev
    target = prev.owner
    warscore_cost = 50
}
                
set_timed_relation_flag = { 
    flag = no_coms who = event_target:MyCountry 
    days = 90 
}

add_opinion_modifier                        # Gives an opinion modifier to an empire.
= {
    who = event_target:MyCountry
    modifier = opinion_crew_saved
}

set_policy                                  # Sets a policy to a specific value
= {
    policy = slavery
    option = slavery_allowed_all
    cooldown = no
}

set_subject_of                              # sets the scope country's overlord to target
= {
    who = root
    subject_type = vassal / protectorate
}

add_threat = {
    who = root
    amount = 4 # scales to pops
}	
     

create_military_fleet = {
    owner = this
    scaled_size = {
        base = 3
    }
}

create_point_of_interest                    # Creates point of interest
= {
    id = anomaly.4035.poi.1
    name = "anomaly.4035.poi_1"
    desc = "anomaly.4035.poi.desc"
    event_chain = star_power_chain
    location = event_target:some_system_1
}

modify_species                              # Creates a new modified species
= {
    species = ROOT
    add_trait = trait_rapid_breeders
    remove_trait = trait_weak
}

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}

###############################
# System (Star)
###############################
set_star_flag = example_flag        # Sets a flag on a star
remove_star_flag = example_flag     # Removes a flag from a star

create_wormhole_station             # Creates a wormhole station
= { 
    owner = last_created_country
    angle = random
}
                                
clear_uncharted_space               # Clears US for country
= {
    from = prevprev
    radius = 5
}

# Creates a new star system with planets
spawn_system = { initializer = "special_init_03" }
spawn_system = {
    min_distance = 20
    max_distance = 50
    system = "sol_system"
}

set_variable                # Sets a variable value
= { 
    which = var 
    value = 1 
}

change_variable             # Changes a variable value
= { 
    which = var 
    value = 1 
}

set_timed_star_flag         # Sets a timed flag on a star
= { 
    flag = day_0 
    days = 7 
}
###############################
# Planet
###############################
tooltip = "text"
planet_event = { id = "id" days = 1 random = 1 }    # fires a Planet event

assign_leader = last_created_leader         # Assigns a leader to either a fleet, army, or pop faction

add_anomaly = TUTORIAL_CAT                          # Adds a specified anomaly to planet
add_minerals = 500                                  # Adds Minerals to a planet, tile or country
add_physics = 10                                    # Adds Physics resources to a planet
add_society = 10                                    # Adds Society resources to a planet
add_engineering = 10                                # Adds Engineering resources to a planet
add_colony_progress = 10                            # Add progress to a colony

cancel_terraformation = yes                         # Cancels terraformation on the planet
change_pc = pc_continental                          # Change planet class of planet.
change_planet_size = 5                              # Adds/Removes onto the size of the planet.
create_mining_station = { owner = ROOT }            # Creates a mining station
create_research_station = { owner = ROOT }          # Creates a research station

destroy_colony = yes                    # Destroys the colony on the planet
destroy_ambient_object = this           # Destroys an ambient object
destroy_country = yes                   # Removes a flag from a country
purge = no                              # Starts/stops purging pops
prevent_anomaly = no                    # Sets if this planet will generate new anomalies.

set_controller = ROOT                   # Sets the controller of a planet
set_ring = yes                          # Adds or removes the ring around a planet
set_owner = ROOT                        # Sets the owner of a planet or fleet.
set_planet_flag = example_flag          # Sets a flag on a planet
set_primitive_age = industrial_age      # Sets a primitive age on a country
set_capital = ROOT                      # Sets planet to capital of a country
set_name = "name"                       # Changes the name of a scope target
set_planet_max_health = 1000            # Sets the maximum health of a planet
set_planet_health = 1000                # Sets the current health of a planet
set_spaceport_level = 6                 # Sets the level of the spaceport

start_colony = ROOT                     # Starts a colony

remove_planet_flag = example_flag       # Removes a flag from a planet
remove_modifier = example_modifier
remove_spaceport_module = "Name" or 1   # Removes a spaceport module from a spaceport. Argument is either a spaceport module slot number or a spaceport module tag

unassign_leader = this                  # Unassigns a leader from scope

add_threat                              # Adds threat
= {
    who = controller
    amount = 10 # scales to pops
}	
        
add_modifier                            # Gives a specific modifier to a planet.
= {
    modifier = "example_modifier"
    days = -1
}

set_timed_planet_flag                   # Sets a timed flag on a planet
= { 
    flag = day_0 
    days = 7 
}

create_spaceport                        # creates a spaceport around planet
= {
    owner = last_created_country
    initial_module = "fallen_empire_weapon"
}
                
create_colony                           # Creates a colony
= {
    owner = last_created_country
    #species = ROBOT_POP_SPECIES_3
    species = owner_main_species
    ethos = owner
}

create_rebels                           # Creates a new rebel country
= {
    name = random
    government = random
    species = prev
    ethos = {
        ethic = "ethic_militarist"
    }
    flag = random
}

create_pop                              # Creates a new pop
= {
    species = event_target:RefugeeAliens / last_created
    ethos = {
        ethic = "ethic_xenophile"
        ethic = "ethic_fanatic_individualist"			
    }
    ethos = owner
}

create_army                             # Creates a new army
= {
    name = "Invading Horde"
    owner = event_target:subterranean_nation
    species = event_target:subterranean_species
    type = "industrial_army"
    leader = last_created_leader
}
            
create_species                          # Creates a new species
= { 
    name = "AI" / random
    class = AI / ART / etc
    portrait = random 
    traits = random
    homeworld = event_target:WarriorHomePlanet # optional
}

modify_species                              # Creates a new modified species
= {
    species = ROOT
    add_trait = trait_rapid_breeders
    remove_trait = trait_weak
}

surveyed                                    # Sets a planet as surveyed by a specific country
= {
    set_surveyed = yes
    surveyor = event_target:ship_owner
}
    
enable_special_project                      # Enables a special research project for a country
= {
    name = "DERELICT_SHIP_PROJECT"
    owner = root
    location = this
}
     
create_ambient_object = {
    type = "derelict_ship_object"
    location = from
}
   
create_country                              # Creates a new country
= {  # Each part is optional aside from type
    name = "Refugees" / random
    type = faction
    name_list = "PRT2"
    government = random
    auto_delete = yes
    ethos = {
        ethic = "ethic_xenophile"
        ethic = "ethic_militarist"
    }
    day_zero_contact = no
    flag = random
    flag = {
        icon = {
            category = "pirate"
                file = "flag_pirate_7.dds"
            }
            background = {
                category = "backgrounds"
                file = "00_solid.dds"
            }
            colors = {
                "red"
                "red"
                "null"
                "null"
            }
        }
}

create_pop_faction                      # creates a pop faction
= {
    type = slave
    pop = root
}

set_spaceport_module                    # Sets a spaceport module at specified slot
= {
    slot = 1
    module = "destroyer_assembly_yards"
}

set_variable                        # Sets a variable value
= { 
    which = var 
    value = 1 
}

change_variable                             # Changes a variable value
= { 
    which = var 
    value = 1 
}
   
create_point_of_interest                    # Creates point of interest
= {
    id = anomaly.4035.poi.1
    name = "anomaly.4035.poi_1"
    desc = "anomaly.4035.poi.desc"
    event_chain = star_power_chain
    location = event_target:some_system_1
}

create_ambient_object                       # Creates a new ambient object of type <type> at location <location>
= {
    type = "derelict_ship_object"
    location = solar_system
}
   
# Creates a new star system with planets
spawn_system = { initializer = "special_init_03" }
spawn_system = {
    min_distance = 20
    max_distance = 50
    system = "sol_system"
}

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}
     
###############################
# Army
###############################
assign_leader = last_created_leader     # Assigns a leader to either a fleet, army, or pop faction

remove_army = yes                       # Removes scope army.

unassign_leader = this                  # Unassigns a leader from scope

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}

###############################
# Ship
###############################
tooltip = "text"
ship_event = { id = example_event.1 }   # fires a Ship event

assign_leader = last_created_leader         # Assigns a leader to either a fleet, army, or pop faction

set_ship_flag = "name"              # Sets a flag on a ship
set_name = "name"                   # Changes the name of a scope target
set_disable_at_health = 100         # Set the amount of health that a ship disables at
set_disabled = no                   # Used to enable or disable a ship

repair_ship = yes                   # Restores a damaged ship to its full HP
reduce_hp_percent = 10              # Reduces the hitpoints of a ship by the percentage given
reduce_hp = 100                     # Reduces the hitpoints of a ship by the points given
remove_ship_flag = "name"           # Removes a flag from a ship
remove_modifier = example_modifier

unassign_leader = this                  # Unassigns a leader from scope

add_modifier                        # Gives a specific modifier to a ship.
= {
    modifier = "example_modifier"
    days = -1
}

set_timed_ship_flag                 # Sets a timed flag on a ship
= { 
    flag = day_0 
    days = 7 
}

enable_special_project              # Enables a special research project for a country
= {
    name = "DERELICT_SHIP_PROJECT"
    owner = root
    location = this
}

# Creates a new star system with planets
spawn_system = { initializer = "special_init_03" }
spawn_system = {
    min_distance = 20
    max_distance = 50
    system = "sol_system"
}

modify_species                              # Creates a new modified species
= {
    species = ROOT
    add_trait = trait_rapid_breeders
    remove_trait = trait_weak
}

create_point_of_interest                    # Creates point of interest
= {
    id = anomaly.4035.poi.1
    name = "anomaly.4035.poi_1"
    desc = "anomaly.4035.poi.desc"
    event_chain = star_power_chain
    location = event_target:some_system_1
}

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}

###############################
# Fleet
###############################
fleet_event = { id = example_event.1 }  # fires a Fleet event

add_mission_progress = -0.2             # Adds progress to a mission
assign_leader = last_created_leader     # Assigns a leader to either a fleet, army, or pop faction

clear_fleet_actions = ROOT              # Clears all fleet actions for fleet on the right side of =
clear_orders = yes                      # Removes all orders from a fleet.
create_army_transport = ROOT            # Creates a new army in space

dismantle = yes                         # Dismantles a station
destroy_fleet = ROOT                    # Destroys fleet on the right side of =

order_forced_return = yes               # Orders a fleet to move back into safe territory.

set_controller = ROOT                   # Sets the controller of a planet
set_fleet_flag = example_flag           # Sets a flag on a fleet
set_fleet_stance = aggressive           # Sets the stance of scope fleet. valid stances are aggressive, passive and evasive
set_aggro_range_measure_from = self     # Sets where aggro range is measured from on a fleet or a country. valid targets: self, return_point 
set_aggro_range = 500                   # Sets aggro range on a fleet or a country
set_owner = ROOT                        # Sets the owner of a planet or fleet.
set_name = "name"                       # Changes the name of a scope target
set_event_locked = yes                  # Locks a fleet actively disabling it to do anything. Remember to unlock.
set_spaceport_level = 6                 # Sets the level of the spaceport
set_formation_scale = 2                 # set formation scale on a fleet
set_leader = "name"                     # Sets a leader from a previously exiled leader associated by a custom name
set_mission = "name"                    # Sets the current mission of an observation station

remove_fleet_flag = example_flag        # Removes a flag from a fleet
remove_modifier = example_modifier
remove_spaceport_module = "Name" or 1   # Removes a spaceport module from a spaceport. Argument is either a spaceport module slot number or a spaceport module tag

unassign_leader = this                  # Unassigns a leader from scope

add_modifier                            # Gives a specific modifier to a fleet.
= {
    modifier = "example_modifier"
    days = -1
}

set_timed_fleet_flag                    # Sets a timed flag on a fleet
= { 
    flag = day_0 
    days = 7 
}

create_ship                             # Creates a new ship
= {
    graphical_culture = "pirate_01"
    name = "Life Tree Protector"
    design = "Large Space Organism"
}

create_ship_design                      # Creates a new ship design
= {
    design = "Reaver"
    ftl = event_target:owner_country
}

set_location                            # Sets the location of a fleet.
= {
    target = PREVPREV
    distance = 35
    angle = random 
}

set_spaceport_module                    # Sets a spaceport module at specified slot
= {
    slot = 1
    module = "destroyer_assembly_yards"
}
            
queue_actions                           # Add actions to fleet's action queue
= {
    wait = {
        duration = 10
        random = 3
    }
    
    orbit_planet = ROOT
    
    move_to = FROM
    
    effect = {
        id = "blah"
    }
    
    repeat	= {
        max_iterations = 10                 #limits how many times stuff can be repeated
        while = { 			                #AND-trigger. If this trigger fails the repetition will be stopped
            id = "something_unique"	        #this trigger needs a unique ID for save/load to work
        }
        
        move_to = PREV #actions to repeat
    }
    
    find_closest_planet = { #finds the closest planet in the system which fulfills the trigger
    trigger = {
        id = "something_unique"
    }
    found_planet = {	#sets current scope to a planet scope with the found planet
        <fleet actions for when a planet was found>
    }
    failed = { #no scope changes
        <fleet action for when no planet was found>
    }
    
    find_random_system = {
        trigger = {
        }
        found_system = {
            move_to = this
        }
    }
}
       
set_variable                        # Sets a variable value
= { 
    which = var 
    value = 1 
}

change_variable                             # Changes a variable value
= { 
    which = var 
    value = 1 
}

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}
       
###############################                        
# Leader
###############################
add_skill = 5                           # Adds amount of skill levels to scope leader
add_trait = leader_trait_maniacal       # Adds a trait to a leader
add_experience = 100                    # Adds specified amount of experience to specified skill on scope leader
  
set_age = 1                             # Changes the age of the leader
set_leader_flag = example_flag          # Sets a flag on a leader
set_name = "name"                       # Changes the name of a scope target
set_skill = 5                           # Sets skill levels to scope leader

recruitable = yes                       # Sets recruitable tag on leader.
remove_leader_flag = example_flag       # Removes a flag from a leader
remove_trait = "traitname"              # Removes a trait from a leader

unassign_leader = this                  # Unassigns a leader from scope

create_leader                           # Creates a new leader
= {
    type = admiral
    species = last_created
    name = "0101010111"
    skill = 400
    traits = {
        trait = leader_trait_aggressive
        trait = leader_trait_fleet_logistician
    }
}

kill_leader                             # Kills leaders of specified types. kill_leader = { type = general type = scientist etc. }
= {                     
    type = scientist 
    show_notification = no
}
    
set_variable                            # Sets a variable value
= { 
    which = var 
    value = 1 
}

change_variable                             # Changes a variable value
= { 
    which = var 
    value = 1 
}

###############################     
# Tile
###############################
add_minerals = 500                      # Adds Minerals to a planet, tile or country
add_deposit = d_vast_society_deposit    # Adds a deposit to a tile
add_building_construction = "building"  # Adds a construction of specified building on tile.

set_building = "building"               # Adds a construction of specified building on tile.
set_ruined = yes                        # Sets the ruined status of a building
set_blocker = tb_noxious_swamp          # Sets a specified blocker on tile.

remove_building = "building"            # Removes building on tile.
remove_blocker = yes                    # Removes blocker from tile. (bool)
clear_deposits = yes                    # Removes all deposits from a tile

create_pop                              # Creates a new pop
= {
    species = event_target:RefugeeAliens / last_created
    ethos = {
        ethic = "ethic_xenophile"
        ethic = "ethic_fanatic_individualist"			
    }
    ethos = owner
}
      
add_resource                            # Adds a resource to a planet or tile
= {
    resource = energy
    amount = 2
    replace = yes
}

###############################
# Pops
###############################
tooltip = "text"
pop_event = { id = henrik.138 }             # fires a Pop event

assign_leader = last_created_leader         # Assigns a leader to either a fleet, army, or pop faction

change_pop_species = PREV                   # Changes the species of a pop.

enslave_pop = yes                           # Enslave/Emancipate pop
kill_pop = yes                              # Kills pop
kill_pop_faction = yes

force_faction_evaluation = this             # forces a pop to evaluate factions

pop_migration = 1                           # Sets the migration speed of a pop.
pop_add_ethic = ethic_fanatic_pacifist      # Adds an ethic to a pop
pop_remove_ethic = ethic_fanatic_militarist # Removes an ethic to a pop
purge = no                                  # Starts/stops purging pops

set_pop_flag = "SUPER_DUPER_FLAG"           # Sets a flag on a pop
set_pop_faction_flag = mandated_release
    
remove_pop_flag = "SUPER_DUPER_FLAG"        # Removes a flag from a pop
remove_pop_faction_flag = mandated_release
remove_modifier = example_modifier

unassign_leader = this                  # Unassigns a leader from scope

add_modifier                                # Gives a specific modifier to a pop.
= {
    modifier = "example_modifier"
    days = -1
}

modify_species                              # Creates a new modified species
= {
    species = ROOT
    add_trait = trait_rapid_breeders
    remove_trait = trait_weak
}

create_point_of_interest                    # Creates point of interest
= {
    id = anomaly.4035.poi.1
    name = "anomaly.4035.poi_1"
    desc = "anomaly.4035.poi.desc"
    event_chain = star_power_chain
    location = event_target:some_system_1
}

set_timed_pop_flag                          # Sets a timed flag on a pop
= { 
    flag = day_0 
    days = 7 
}

###############################
# Pop Faction
###############################
pop_faction_event = { id = pop.1 }          # fires a Pop faction event
add_support = 20                            # Adds to a pop factions Support level
set_pop_faction = "faction"                 # Makes a pop join a faction
set_support = 20                            # Sets a pop factions Support level
set_pop_faction_flag = "flag"               # Sets a flag on a pop
remove_pop_faction_flag = "flag"            # Removes a flag from a pop
kill_pop_faction = yes                      # Deletes a pop faction

set_timed_pop_faction_flag                  # Sets a timed flag on a pop faction
= { 
    flag = day_0 
    days = 7 
}
###############################
# Ambient Object
###############################
set_ambient_object_flag = "flag"        # Sets a flag on a AmbientObject
remove_ambient_object_flag = "flag"     # Removes a flag from a AmbientObject
set_timed_ambient_object_flag           # Sets a timed flag on a ambient object
= { 
    flag = day_0 
    days = 7 
}

enable_special_project                  # Enables a special research project for a country
= {
    name = "DERELICT_SHIP_PROJECT"
    owner = root
    location = this
}

---------------------------------------------------------------

###############################
# Triggers
###############################
# Note: > and < can be used instead of = for inclusive checks.

always = yes                                        # Always counts as TRUE
exists = ROOT                                       # Checks if object exists
years_passed > 5                                    # Compares the number of years that have passed since game start with a value
text = "test"                                       # Adds text to trigger
local_has_dlc = "Paradox Account Sign-up Bonus"     # Checks for DLC
custom_tooltip_fail = "text"                        # Shows custom text when trigger is failing
logged_in_to_pdx_account = yes                      # Checks if the local human is logged in to a Pdx account. This WILL cause an out of sync if used for anything that can change the game state
host_has_dlc = "name"                               # Checks if the host has a certain dlc enabled
local_has_dlc = "name"                              # Checks if the host has a certain dlc enabled

is_ironman = yes                                    # Checks if the game is in Ironman
is_multiplayer = yes                                # Checks if the game is running in multiplayer
is_same_value = event_target:MyCountry              # Checks if two scopes have the same value
is_scope_valid = yes                                # Checks if the current scope is valid

has_ambient_object_flag = manufactory               # Checks if an ambient object has a specified flag

###############################
# Switch
###############################
Used in the desc = { } of events

Can use any trigger for the current scope as a RHA

The modifier itself is the key (as a scope), with it's contents being effect
switch = {
    trigger = has_modifier
    hazardous_weather = { text = anomaly.6660.desc.weather }
    weak_magnetic_field = { text = anomaly.6660.desc.magnetic }
}

###############################
# War
###############################
war_demand_counter = ?                              # Compares a war demand trigger
attacker_war_score = 10                             # Checks the war score of the attackers in a war
defender_war_score = 10                             # Checks the war score of the defenders in a war

is_war_participant                                  # Checks if a country is participating in scope war
= {
    who = prevprev
    side = prev
}

count_war_participants = {
    side = root
    limit = { }
    count > 0
}

count_potential_war_participants = {
    side = root
    limit = { }
    count > 0
}

###############################
# Alliance
###############################
members = 2                                         # Compares the number of alliance members

###############################
# Sector
###############################
is_core_sector = yes                                # Checks if the current sector is the country's core sector

###############################
# Country
###############################
check_variable = { which = var value = 0 }          # Compares the variable value
has_global_flag = example_flag                      # Checks a global trigger

has_event_chain = example_chain                     # Checks if the country has an event chain
has_policy_flag = interference_passive              # Checks if a country has a policy
has_country_flag = example_flag                     # Checks if a country has a specified flag

has_edict = crystal_sonar                           # Checks if a planet or country has an edict activated
has_technology = tech_mine_satramene                # Checks if a country has a technology of atleast a specific level
has_government = indirect_democracy                 # Checks if a country has a specified government
has_tech_option = tech_fission_power                # Checks if a country has a technology option
has_communications = PREV                           # Checks if country has communication with another country
has_ai_personality = honorbound_warriors            # Checks if an Empire has a certain personality type
has_ai_personality_type = aggressive                # Checks if an Empire has a certain personality type
has_ai_personality_behaviour = conqueror            # Checks if an Empire has a certain personality type
has_valid_ai_personality = yes                      # checks if a country has a valid ai
has_country_edict = "edictname"                     # Checks if a country has an edict
has_surveyed_class = pc_desert                      # Checks a country has surveyed planet class trigger
has_ai_personality_behaviour = uplifter
has_election_type = none                            # Checks if a country has a specified election type: none / democratic / oligarchy
has_alliance = yes                                  # Checks if a country is in an alliance (bool)
has_federation = yes                                # Checks if a country is in an federation (bool)
has_opinion_modifier = yes                          # Checks if the country has an opinion modifier
has_modifier = "name"                               # Checks if scope object has a modifier
has_truce = ROOT                                    # Checks if a country has truce with certain country
has_access_military = ROOT                          # Checks if a country has military access to a system
has_access_civilian = ROOT                          # Checks if a country has civilian access to a system
has_access_construction = ROOT                      # Checks if a country has constraction access to a system
has_country_strategic_resource = yes                # Compares the resources of a country.
has_special_project = yes                           # Checks if a country has a special project available

grants_migration_access = ROOT                      # Checks if a country grants migration access to anyone
has_migration_access = ROOT                         # Checks if scope country has migration access to target country

has_ethic = "ethicname"             # Checks if an empire's dominant species has a certain Ethic
has_trait = "traitname"             # Checks if an empire's dominant species, pop, or leader has a certain Trait
has_existing_ship_design = "name"   # Checks if a country has a specific ship design
has_faction = "name"                # Checks if an empire has a certain faction type
has_point_of_interest = "name"      # Checks if the scope location has a point of interest

is_country_type = primitive     # Checks if country is of specified type
is_advisor_active = no          # Checks if a country has an advisor
is_country = ROOT               # Checks if a country is of the same as the scope
is_hostile = from               # Checks if country is hostile against a target
is_federation_leader = yes      # Checks if a country is a federation leader
is_at_war = yes                 # Checks if a country is at war
is_primitive = yes              # Checks if a country is primitive (bool)
is_ai = no                      # Checks if a country is an AI
is_pirate = yes                 # Checks if a country is a pirate country (bool)
is_same_empire = ROOT           # Checks if an empire is the same as another
is_same_species = ROOT          # Checks if a pop or empire is of the same species as another pop or empire
is_at_war_with = ROOT           # Checks if an empire is at war with another empire
is_same_species_class = ROOT    # Checks if a pop or empire is of the same species class as another pop or empire
is_tutorial_level = 1           # Compares the tutorial level of the player of a country.
is_species_class = "human"      # Checks if the founder species of a country, or a pop is of a specific species
is_rim_system = yes             # Checks if a system is on the galactic rim
is_war_leader = yes             # Checks if country is war leader
is_in_alliance_with = ROOT      # Checks if country is in an alliance with target country
is_in_federation_with = ROOT    # Checks if country is in a federation with target country
is_guaranteeing = ROOT          # Checks if scope country is guaranteeing target country
is_threatened_to = ROOT         # Attitude check, if country is threatened by target country
is_protective_to = ROOT         # Attitude check, if country is protective of target country
is_friendly_to = ROOT           # Attitude check, if country is friendly to target country
is_hostile_to = ROOT            # Attitude check, if country is hostile to target country
is_dismissive_to = ROOT         # Attitude check, if country is dismissive of target country
is_patronizing_to = ROOT        # Attitude check, if country is patronizing to target country
is_angry_to = ROOT              # Attitude check, if country is angry at target country
is_neighbor_of = ROOT           # Checks if country is neighbors with target
is_rival = ROOT                 # Attitude check, if country is a rival of target country
is_unfriendly_to = ROOT         # Attitude check, if country is unfriendly to target country
is_loyal_to = ROOT              # Attitude check, if country is loyal to target country
is_disloyal_to = ROOT           # Attitude check, if country is disloyal to target country
is_cordial_to = ROOT            # Attitude check, if country is cordial to target country
is_domineering_to = ROOT        # Attitude check, if country is domineering towards target country
is_wary_to = ROOT               # Attitude check, if country is wary of target country
is_subspecies = yes             # checks if a pop or empire is a subspecies of the same species as another pop or empire
is_valid = yes                  # Checks to see if the target of a scope is valid
is_proposing_war_demands = yes  # Checks if currently proposing wardemands or handling existing wardemands

can_change_policy = "policy"    # Checks if a country can change anything with a policy
can_declare_war = yes           # Checks if we can declare war against a target
can_create_sector = ?           # Checks if a sector can be created on the targeted planet
ideal_planet_class = pc_arid    # Checks the ideal planet class of a target country
graphical_culture = "MAM"       # Checks if a country has specified graphical culture
free_leader_slots = 2           # Compares the number of free leader slots
last_changed_policy = slavery   # checks the last changed policy of a country against specified policy
opposing_ethics_divergence = ROOT   # Compares the opposing ethics divergence.
galaxy_percentage = 40          # Checks if the scope owns systems corresponding to a certain galaxy percentage
fleet_power = 100               # Checks country fleet power
would_join_war = ROOT           # Checks if a country would join the side of a certain country in a hypothetical war
can_be_subject = ROOT           # Checks if country can be subject of 'subject_type' under 'overlord'
subject_can_diplomacy = yes     # Checks if we are allowed by our overlord to do certain diplomatic actions
species_portrait = "MAM"        # Checks if a species uses a certain portrait.


num_fleets < 2                  # Checks if a country has the said number of fleets
num_ships < 3                   # Checks if a country has the said number of ships
num_communications > 0          # Compares the number of planets on a planet with a value
num_owned_planets = 1           # Compares the number of owned planets in a country with a value
num_rare_techs > 0              # Compares number of researched rare technologies
num_pops > 0                    # Compares the number of planets on a planet with a value
num_ethics = 2                  # Compares the number of ethics with a value
num_traits < 3                  # compares the number of traits with a value
num_armies = 5                  # checks if a country has the said number of armies

off_war_score_sum > 0           # Checks the sum of war score in all offensive wars
def_war_score_sum < 0           # Checks the sum of war score in all defensive wars
vassals > 2                     # Compares the number of vassals
sectors = 5                     # Compares number of sectors
sectors_over_limit = 0          # Compares number of sectors over the limit
last_increased_tech = "name"    # Compares against the last increased tech of a country

influence > 50                  # Checks country influence
energy > 49                     # Checks for country energy

running_balance = 100           # Compares country running balance.
balance = 100                   # Compares country balance.
income = 100                    # Compares country income.
expenses = 100                  # Compares country expenses.
construction_expenses = 10      # Compares the previous months construction expenses of a country.
federation_expenses = 10        # Compares the previous months federation expenses of a country.
produced_energy = 100           # Compares the amount of produced energy of a country.
trade_income = 100              # Compares the previous months expenses from the trade of a country.
ship_maintenance = 100          # Compares the previous months ship maintenance of a country.
army_maintenance = 100          # Compares the previous months army maintenance of a country.
colony_maintenance = 100        # Compares the previous months colony maintenance of a country.
station_maintenance = 100       # Compares the previous months station maintenance of a country.

stored_physics_points = 100     # Compares the amount of stored physics points a country has.
stored_society_points = 100     # Compares the amount of stored society points a country has.
stored_engineering_points = 100 # Compares the amount of stored engineering points a country has.


count_tech_options              # Untested: Compares the amount of tech options a country has against a value, can specify which area
= {
    area = society
    value = 10
}

has_relation_flag                   # Checks for relation flags
= { 
    who = root 
    flag = AbandonedRefugees 
}

reverse_has_relation_flag           # # Checks for reverse relation flags
= { 
    who = root 
    flag = AbandonedRefugees 
}

has_completed_event_chain_counter   # Checks if the country has completed counter in event chain.
= {
    event_chain = star_power_chain
    counter = systems_visited_poi
}

has_established_contact             # Checks if the country has contact with another country.
= { 
    who = event_target:MyCountry 
}

intel_level                         # checks if scope-country has intel level </>/= [level] in [system] ( intel_level = { level > low system = FROMFROM } )
= { 
    level > low 
    system = this 
}

their_opinion                       # Checks target country's opinion value of this country
= {
    who = event_target:book_writer
    value < 11
}

opinion = {
    who = target
    value < 10
}
        
has_monthly_income                  # Checks monthly income of resource compared against specific value
= {
    resource = minerals
    value > 250
}    

has_country_resource                # Compares the stored resources of a country.
= {
    type = minerals
    amount > 99
} 

tech_unlocked_ratio                 # Ratio of tech between this and from
= {
    who = from
    ratio > 5
}   

research_leader = {
    area = engineering
    has_trait = "leader_trait_expertise_materials"
}

num_killed_ships                    # Compares how many ships scope country has killed of [target]
= {
    target = from
    value < 10
}

num_taken_planets                   # Compares how many planets scope country has taken from [target]
= {
    target = from
    value = 0
}

count_armies                        # Counts the amount of armies which fill a requirement and compare it to a number
= {
    limit = { always = yes }
    count > 1
}

###############################
# System
###############################
starting_system = ROOT              # Checks if a system is the starting system for an empire

###############################
# Planet
###############################
check_variable = { which = var value = 0 }  # Compares the variable value
has_global_flag = example_flag              # Checks a global trigger
has_star_flag = "flagname"                  # checks if a star has a specified flag
has_planet_flag = "flagname"                # Checks if a planet has a specified flag
has_planet_class = "planetclass"            # Checks if a star has planet of certain class

is_owned_by = ROOT                          # Checks if a planet or galactic object is owned by target empire
is_controlled_by = ROOT                     # Checks if a planet is controlled by a certain country
is_planet = ROOT                            # Checks if a planet is of the same as the scope
is_star_class = sc_pirate_system            # Checks if a planet star is of a certain class
is_planet_class = pc_arctic                 # Checks if a planet is of a certain class
is_capital = no                             # Checks if a planet is its owners capital
is_moon = yes                               # Checks if a planet is a moon
is_asteroid = yes                           # Checks if a planet is an asteroid
is_ringworld = no                           # Checks if a planet is a ringworld
is_star = no                                # Checks if a planet is a star
is_homeworld = no                           # Checks if a planet is its owners homeworld
is_sentient = no                            # Checks if a pop is sentient
is_terraformed = yes                        # Checks if a planet has ever been terraformed
is_terraforming = yes                       # Checks if a planet is being terraformed right now
is_inside_nebula = yes                      # Checks if a planet/ship is inside a nebula
is_in_cluster = resource_cluster_0          # Checks if a galactic object belongs to a cluster
is_colonizable = yes                        # Checks if a planet is colonizable (bool)
is_inside_border = ROOT                     # Checks if a planet/ship/fleet is inside the border of the specified country
is_occupied_flag = yes                      # Checks if a planet is under military occupation
is_colony = yes                             # Checks if a planet is a colony
is_preventing_anomaly = yes                 # Checks if a planet is currently preventing anomalies
is_rim_system = yes                         # Checks if a system is on the galactic rim
is_ideal_planet_class = "name"              # Checks if a planet is of ideal class for country
is_neighbor_of = ROOT                       # Checks if country is neighbors with target
is_under_colonization = yes                 # Checks if a planet is being colonized (bool)
is_valid = yes                              # Checks to see if the target of a scope is valid
is_spaceport_module_slot_free = "name"      # Checks if a specific spaceport module slot is free
is_proposing_war_demands = yes              # Checks if currently proposing wardemands or handling existing wardemands

has_strategic_resource = "resourcename"     # Checks if a planet has a specific strategic resource
has_deposit = "d_immense_mineral_deposit"   # Checks if a tile/planet has a deposit
has_anomaly = yes                           # Checks if a planet has a anomaly
has_planet_modifier = "example"             # Checks if a planet has a planet modifier
has_ground_combat = no                      # Checks if a planet has ground combat
has_any_strategic_resource = no             # Checks whether a planet has any strategic resource (bool)
has_army = yes                              # Checks if a planet has an army
has_planet_edict = "edictname"              # Checks if a planet has an edict
has_building = "buildingname"               # Checks if a planet or tile has a building
has_grown_pop = no                          # Checks if a planet or tile has a grown pop
has_growing_pop = no                        # Checks if a planet or tile has a growing pop
has_owner = yes                             # Checks if a planet is colonized
has_ring = yes                              # Checks if a planet has a ring or not
has_building_construction = yes             # Checks if a planet or tile has a building construction
has_blocker = no                            # Checks if a planet or tile has a blocker
has_edict = crystal_sonar                   # Checks if a planet or country has an edict activated
has_observation_outpost = yes               # Checks if a planet has an observation outpost
has_mining_station = no                     # Checks if a planet has a mining station
has_research_station = no                   # Checks if a planet has a research station
has_spaceport = yes                         # Checks if a planet has a spaceport
has_moon = yes                              # Checks if a planet has a moon
has_deposit_for = "shipname"                # Checks if a tile has a deposit for specific ship class
has_modifier = "name"                       # Checks if scope object has a modifier
has_point_of_interest = "name"              # Checks if the scope location has a point of interest
has_orbital_station = yes                   # Checks if a planet has an orbital station
has_colony_progress = 100                   # Checks progress of establishing a colony on planet
has_spaceport_module = "name"               # Checks if a spaceport has a module upgrade
has_free_spaceport_module_slot = yes        # Checks if a spaceport has a free module slot

num_spaceport_modules = 5                   # Compares the parameter to the amount of spaceport modules
num_free_spaceport_module_slots = 5         # Compares the parameter to the amount of free spaceport module slots
num_moons < 2                               # Compares number of moons of planet.
num_minerals > 0                            # Compares the number of minerals on a planet with a value
num_physics = 0                             # Compares the number of physics resources on a planet with a value
num_society = 0                             # Compares the number of society resources on a planet with a value
num_engineering = 0                         # Compares the number of engineering resources on a planet with a value
num_modifiers > 0                           # Compares the number of modifiers on a planet with a value
     
can_build_spaceport_module = "name"         # Checks if a spaceport is allowed to build a specific module upgrade     
can_colonize = yes                          # Checks if a planet is colonizable by a country's founder species
planet_size = ROOT                          # Compares the planet size
free_leader_slots = 2                       # Compares the number of free leader slots
sector_controlled = yes                     # Checks if the planet/fleet is controlled by the sector
original_owner = yes                        # Checks if a planet is still owned by first colonizer

orbital_bombardment = limited               # Checks the orbital bombardment status of a planet: limited / full / soft
fortification_health > 1                    # Compares a value with fortification health percentage
num_pops > 0                                # Compares the number of planets on a planet with a value
colony_age > 240                            # Colony age in months compared with a value
free_pop_tiles < 1                          # Compares a value with the amount of free tiles for pops
free_building_tiles = 0                     # Compares a value with the amount of free tiles for buildings

count_deposits                              # Untested: counts number of deposits of given type on planet or tile
= { 
    type = "name"
    value = 10
}

is_surveyed                                 # Checks if a planet/system as been survey by specified country
= {     
    who = event_target:ship_owner 
    status = no 
}

habitability                                # Checks for species habitability on current planet
= {
    who = prev
    value > 0.5
}

has_resource                                # Compares the resources of planet or tile.
= {
    type = energy
    amount > 0
}

distance                                    # Compares the min/max distance to a target with a value
= {
    source = ROOT
    max_distance = 30
    min_distance = 0
}

count_pops                                  # Counts the amount of pops which fill a requirement and compare it to a number
= {
    limit = { is_growing = no }
    count > 1
}

count_owned_pops                            # Counts the amount of pops which fill a requirement and compare it to a number
= {
    limit = { pop_has_trait = trait_robotic_3 }
    count > 10
}

count_armies                        # Counts the amount of armies which fill a requirement and compare it to a number
= {
    limit = { always = yes }
    count > 1
}

###############################
# Army
###############################
army_type = "armytype"                  # Checks what type an army type is
assault_armies = 2
defense_armies = 1

is_army = ROOT                          # Checks if an army is of the same as the scope

###############################
# Fleet
###############################
check_variable = { which = var value = 0 }      # Compares the variable value
has_global_flag = example_flag                  # Checks a global trigger
has_fleet_flag = "example_flag"                 # Checks if a fleet has a specified flag

free_leader_slots = 2                           # Compares the number of free leader slots
fleet_size > 119                                # Checks fleet size
num_ships < 3                                   # Checks if a country has the said number of ships
sector_controlled = yes                         # Checks if the planet/fleet is controlled by the sector
can_build_spaceport_module = "name"             # Checks if a spaceport is allowed to build a specific module upgrade

num_free_spaceport_module_slots = 5             # Compares the parameter to the amount of free spaceport module slots
num_spaceport_modules = 5                       # Compares the parameter to the amount of spaceport modules

has_mission = technological_enlightenment_1     # Checks if a fleet has a certain mission
mission_progress > 0.2                          # Checks if a mission has a certain progress

has_fleet_order = yes                           # Checks if a ship or a fleet has a fleet order
has_ground_support_stance = "stance"            # Checks if a fleet has a certain bombardment stance
has_spaceport_module = "name"                   # Checks if a spaceport has a module upgrade
has_free_spaceport_module_slot = yes            # Checks if a spaceport has a free module slot

is_spaceport_module_slot_free = "name"          # Checks if a specific spaceport module slot is free
is_inside_nebula = yes                          # Checks if a planet/ship is inside a nebula
is_inside_border = ROOT                         # Checks if a planet/ship/fleet is inside the border of the specified country
is_disabled = yes                               # Checks if a ship or fleet is disabled
is_rim_system = yes                             # Checks if a system is on the galactic rim
is_being_repaired = yes                         # Checks if a fleet or ship is being repaired
is_in_combat = yes                              # Checks if a fleet or ship is being repaired
is_proposing_war_demands = yes                  # Checks if currently proposing wardemands or handling existing wardemands

distance                                        # Compares the min/max distance to a target with a value
= {
    source = ROOT
    max_distance = 30
    min_distance = 0
}

###############################
# Ship
###############################
has_global_flag = example_flag          # Checks a global trigger
has_ship_flag = "example_flag"          # Checks if a planet has a specified flag

is_ship = ROOT                          # Checks if a ship is of the same as the scope
is_ship_class = shipclass_military      # Checks if a ship is a specified class
is_ship_size = mining_station           # Checks if a ship is a specified size
is_inside_nebula = yes                  # Checks if a planet/ship is inside a nebula
is_inside_border = ROOT                 # Checks if a planet/ship/fleet is inside the border of the specified country
is_damaged = yes                        # Checks if a ship is damaged
is_disabled = yes                       # Checks if a ship or fleet is disabled
is_rim_system = yes                     # Checks if a system is on the galactic rim
is_being_repaired = yes                 # Checks if a fleet or ship is being repaired
is_proposing_war_demands = yes          # Checks if currently proposing wardemands or handling existing wardemands

has_hp = 100                            # Compares the hit points of a ship with a value
has_fleet_order = yes                   # Checks if a ship or a fleet has a fleet order
has_point_of_interest = "name"          # Checks if the scope location has a point of interest

free_leader_slots = 2                   # Compares the number of free leader slots
shipclass_military = 1
shipclass_science_ship = 1
shipclass_constructor = 2
shipclass_colonizer = 2
shipclass_transport = 1

count_ships                             # Compares number of ships in a fleet that matches the [limit = {..}]
= {
    limit = { is_ship_class = shipclass_military }
    count > 11
}

count_owned_ships                       # Compares number of ships in a country that matches the [limit = {..}]
= {
    limit = { is_ship_class = shipclass_military }
    count > 11
}

distance                                # Compares the min/max distance to a target with a value
= {
    source = ROOT
    max_distance = 30
    min_distance = 0
}


###############################
# Leader
###############################
has_level = 3                       # Checks if leader has at least specified level of specified skill
has_leader_flag = example_flag      # Checks if a leader has a specified flag
has_trait = "traitname"             # Checks if an empire's dominant species, pop, or leader has a certain Trait
has_skill = 3                       # Checks level of skill for a leader
has_experience = 100                # Checks amount of experience for a leader
has_mandate = yes                   # Checks if a leader has mandate <yes/no/mandate_key>

is_researching_area = engineering   # Checks if a leader is researching a specific area

num_ethics = 2                      # Compares the number of ethics with a value
num_traits < 3                      # compares the number of traits with a value

leader_class = admiral              # Checks if a leader is a specific type
gender = female                     # Checks the gender of a leader

leader = scientist                  # scientist / admiral / general / ruler / governor
leader_of_faction = yes             # Checks if leader is the leader of a faction ( targets yes/no/specific faction )

###############################
# Tile
###############################
has_blocker = no                        # Checks if a planet or tile has a blocker
has_grown_pop = no                      # Checks if a planet or tile has a grown pop
has_growing_pop = no                    # Checks if a planet or tile has a growing pop
has_deposit = "deposit"                 # Checks if a tile/planet has a deposit
has_building_construction = yes         # Checks if a planet or tile has a building construction
has_growing_pop = no
has_deposit_for = "shipname"            # Checks if a tile has a deposit for specific ship class
has_prev_building = "name"              # Checks if a tile previously had a building (only latest building)

is_ruined = no                          # Checks if a building is ruined or not
is_orbital_tile = no                    # Checks if a tile is the tile that stations collect from

num_adjacent_tiles = 2                  # Adjacent tiles with a value

has_resource                            # Compares the resources of planet or tile.
= {
    type = energy
    amount > 0
}

###############################
# Pop
###############################
has_global_flag = example_flag          # Checks a global trigger
has_pop_flag = "testflag"               # Checks if a pop has a specified flag

is_pop = ROOT                           # Checks if a pop is of the same as the scope
is_enslaved = no                        # Checks if a pop is enslaved
is_being_purged = no                    # Checks if a pop is being exterminated
is_robot_pop = no                       # Checks if the pop is of a robotic species class.
is_colony_pop = yes                     # Checks if a pop is a colony pop
is_growing = yes                        # Checks if a pop is growing
is_subspecies = yes                     # checks if a pop or empire is a subspecies of the same species as another pop or empire
is_proposing_war_demands = yes          # Checks if currently proposing wardemands or handling existing wardemands

has_ethic = "ethicname"                 # Checks if an empire's dominant species has a certain Ethic
has_trait = "traitname"                 # Checks if an empire's dominant species, pop, or leader has a certain Trait
has_modifier = "name"                   # Checks if scope object has a modifier
has_pop_faction_flag = "flag"           # Checks if a pop faction has a specified flag

num_ethics = 2                          # Compares the number of ethics with a value
num_traits < 3                          # compares the number of traits with a value
free_leader_slots = 2                   # Compares the number of free leader slots
member_of_faction = yes                 # Checks if pop is a member of a faction ( targets yes/no/specific faction )
support = 2                             # Compares the relative support of a pop faction
opposing_ethics_divergence = ROOT       # Compares the opposing ethics divergence.
species_portrait = "MAM"                # Checks if a species uses a certain portrait.

is_species = "ROBOT_POP_SPECIES_1"      # Checks if the founder species of a country, or a pop is of a specific species
is_pop_faction_type = slave             # Checks if pop faction is specific type
is_same_species = ROOT                  # Checks if a pop or empire is of the same species as another pop or empire
is_same_species_class = ROOT            # Checks if a pop or empire is of the same species class as another pop or empire
is_species_class = "human"              # Checks if the founder species of a country, or a pop is of a specific species
is_rim_system = yes                     # Checks if a system is on the galactic rim

pop_has_ethic = ethic_xenophobe         # Checks if a pop has a certain Ethic
pop_has_trait = trait_decadent          # Checks if a pop has a certain trait

count_pop_factions                      # Counts the amount of pop factions which fill a requirement and compare it to a number
= {
    limit = { is_pop_faction_type = slave }
    count < 1
}

pop_faction = { is_pop_faction_type = planet_separatists }

opposing_ethics_divergence = {
    steps < 2
    who = parameter:country
}
     
check_pop_faction_parameter             # Compares a pop faction parameter against a value
= {
    which = country
    value = parameter:country
}     

happiness   # Compares pop happiness - Scope: pop

distance # Compares the min/max distance to a target with a value
= {
    source = ROOT
    max_distance = 30
    min_distance = 0
}

---------------------------------------------------------------

###############################
# Buildings
###############################
building_<name> = {
    planet_modifier_with_pop_trigger = {
        key = <key>
        potential = {
            owner = {
                has_technology = "<tech>"
            }
        }
        modifier = {}
    }
}

###############################
# Technology
###############################
tech_<name> = {
    weight_modifier = {
        modifier = {
            factor = 0
            NOT = {
                any_planet_within_border = {
                    OR = {
                        is_planet_class = pc_<class>
                    }
                    habitability = {
                        who = root.species # or prev.species, or from.species
                        value < 0.9
                    }
                }
            }
        }
    }
}

tech_<name> = {
}