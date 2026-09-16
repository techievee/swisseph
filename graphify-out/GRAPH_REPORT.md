# Graph Report - swisseph  (2026-09-16)

## Corpus Check
- Large corpus: 158 files · ~3,362,533 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 1544 nodes · 5389 edges · 114 communities (67 shown, 30 thin omitted)
- Extraction: 76% EXTRACTED · 23% INFERRED · 0% AMBIGUOUS · INFERRED: 1266 edges (avg confidence: 0.85)
- Token cost: 0 input · 847,425 output

## Community Hubs (Navigation)
- Android JNI Export Layer
- Date, Time & Leap-Second Core
- Android JNI Core (swecl)
- Nutation & Ayanamsha (JNI)
- Astronomical Phenomena Helpers (JNI)
- JPL Horizons Validation Suite
- Phenomena & Azimuth/Altitude Engine
- Orbital Elements & Sidereal Houses
- graphify Tooling & Exports
- Planetary Theory (JNI)
- Fixed-Star Catalog Engine (JNI)
- Fixed-Star & Orbital Data Files
- Events Engine (swevents)
- Nutation & Delta-T Library
- Windows GUI (Swisseph for Windows)
- Core Library (sweph/swecl)
- Ephemeris Data Files & Test Cases
- setest Multi-Value Reader
- swetest Test Driver & Calls
- Phenomena Helper Functions (swehel)
- setest Checkpoint Framework
- Gauquelin & Ascension Sectors
- House Systems & Library I/O
- JPL Ephemeris (swejpl)
- JPL Ephemeris (JNI)
- Moshier JPL Format Reader
- setest Test Suites
- setest Test-Data Parsers
- setest Config Reader
- Library I/O & File Management (JNI)
- Rise/Set & Magnitudes (JNI)
- Acronychal & Ascension (JNI)
- setest Value-Table Matchers
- setest Utilities (globals)
- Licensing & Contrib Overview
- Fictitious Planets & Elements (JNI)
- Coordinate System Utilities (JNI)
- HORIZONS Observer Settings UI
- Indian Panchang (Saka Era) Table
- HORIZONS Settings Panel (Geocentric)
- HORIZONS Settings (Geocentric #2)
- HORIZONS Settings (Geocentric #3)
- HORIZONS Settings (Jupiter Barycenter)
- Orbital Extremum Search
- Apparent-Position Output (Image 10)
- Light-Time & Deflection Corrections
- Apparent Output (Topocentric, image19)
- Output Table (ObsEcLon/ObsEcLat)
- Indian Calendar: Ayanamsha (Part V)
- Ayanamsha & Nutation API
- HORIZONS Observer Quantities Dialog
- Sun Ephemeris Table (image14)
- Sun Ephemeris Output (image16)
- HORIZONS Target-Body Selection
- Ayanamsha & Nutation-in-Longitude
- Ephemeris Time-Range Parameters
- Ephem Table Output (ICRF, image7)
- Apparent Output (Airless, image12)
- Atmospheric Refraction Option
- $SOE Output Table (image31)
- $SSOE Ephemeris Output (image5)
- Airless-Apparent Coordinate Definition
- HORIZONS Target Search (Mars)
- SEPM Ephemeris File Header (Io)
- Lahiri Ayanamsha (Rashtriya Panchang)
- Extra-Precision Output Option
- Astrological House Systems (6.x)
- 12-Segment Circular Wheel (image1)
- Annual Series Table 1916–1923 (image2)
- Eclipse ObsEclLon/ObsEcLat Sample
- Io Physical Properties (image28)
- Airmass-Apparent Output (image33)
- Ayanamsha Table (Jan 2019)
- Ayanamsha Table (Jan 2020)
- Start-Time Field (TT, image8)
- Ephem Time-Range Output (image9)
- Eclipse & Heliacal Events (5.x)
- Osculating vs. Natural Apogee/Lilith
- True & Mean Lunar Node
- Delta-T Table & swe_deltat_ex
- setest Shell Test (test)
- setest Shell Test (mytest_ok)
- setest Shell Test (read_section)
- setest Shell Test (test.sh)
- Swisseph 'Inside' Logo
- ObsEclLon/ObsEcLat Sample (b9901)
- National Panchang (Devanagari)
- Professional License Contract (Jun 2026)
- Programmer's Interface Manual (PDF)
- Eclipse & Occultation API (8.x)
- House Functions API
- Sidereal Mode API
- Placidus House Improvement (SE 2.09)
- Planetary Nodes & Apsides (2.2.5)
- Release History (v1.00–v2.10.03)
- VSOP87 Analytical Planetary Theory
- What Is Missing (Ch. 30)

## God Nodes (most connected - your core abstractions)
1. `swe_degnorm()` - 70 edges
2. `swe_calc()` - 64 edges
3. `swe_degnorm()` - 62 edges
4. `swe_deltat_ex()` - 47 edges
5. `main()` - 47 edges
6. `swe_calc()` - 45 edges
7. `swe_deltat_ex()` - 42 edges
8. `swe_heliacal_pheno_ut()` - 31 edges
9. `swi_precess()` - 30 edges
10. `swe_heliacal_pheno_ut()` - 30 edges

## Surprising Connections (you probably didn't know these)
- `SE1 Compressed Ephemeris Data Files (.se1)` --references--> `swe_calc()`  [INFERRED]
  readme.md → sweph.c
- `seleapsec.txt Leap Second Dates` --references--> `swe_jdet_to_utc()`  [INFERRED]
  seleapsec.txt → swedate.c
- `astlistn.md Asteroid List` --references--> `swe_calc()`  [INFERRED]
  ephe/astlistn.md → sweph.c
- `plmolist.txt Planetary Moon Numbers and Body Centers` --references--> `swe_calc()`  [INFERRED]
  ephe/sat/plmolist.txt → sweph.c
- `seasnam.txt Asteroid Names File` --references--> `swe_calc()`  [INFERRED]
  ephe/seasnam.txt → sweph.c

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **graphify Runbook: SKILL.md and its reference documents** — _claude_skills_graphify_skill, _claude_skills_graphify_references_add_watch, _claude_skills_graphify_references_exports, _claude_skills_graphify_references_extraction_spec, _claude_skills_graphify_references_github_and_merge, _claude_skills_graphify_references_hooks, _claude_skills_graphify_references_query, _claude_skills_graphify_references_transcribe, _claude_skills_graphify_references_update [EXTRACTED 1.00]
- **Graph Query Flow: vocab expansion, traversal, path, explain, save-result feedback** — _claude_skills_graphify_references_query_vocab_expansion, _claude_skills_graphify_references_query_traversal, _claude_skills_graphify_references_query_path, _claude_skills_graphify_references_query_explain, _claude_skills_graphify_references_query_save_result [INFERRED 0.85]
- **Optional Export Targets (flag-gated, all consuming graph.json)** — _claude_skills_graphify_references_exports_wiki, _claude_skills_graphify_references_exports_neo4j, _claude_skills_graphify_references_exports_falkordb, _claude_skills_graphify_references_exports_mcp, _claude_skills_graphify_references_exports_benchmark [INFERRED 0.85]
- **Swiss Ephemeris Runtime Data Files (consumed via ephepath)** — ephe_sefstars_txt, ephe_seorbel_txt, ephe_seasnam_txt, ephe_astlistn_md, ephe_sat_plmolist_txt, ephe_swe_deltat_inactive_txt, ephe_seleapsec_txt, swephlib_swephlib_c_swe_set_ephe_path [INFERRED 0.85]
- **The three selectable ephemeris backends of swe_calc() (JPL / Swiss compressed / Moshier)** — doc_swisseph_swisseph_product, doc_swisseph_jpl_de431, doc_swisseph_moshier_ephemeris [EXTRACTED 1.00]
- **The selectable ayanamsha families behind swe_set_sid_mode() (Fagan/Bradley, Lahiri, Krishnamurti, galactic)** — doc_swisseph_sidereal_aynamsha, doc_swisseph_fagan_bradley, doc_swisseph_lahiri, doc_swisseph_krishnamurti, doc_swisseph_galactic_ayanamsha [INFERRED 0.85]
- **House-system computation stack (methods, Placidus improvement, polar fallback, Gauquelin sectors)** — doc_swisseph_house_systems, doc_swisseph_placidus_improvement, doc_swisseph_house_cusp_polar, doc_swisseph_house_position_gauquelin [INFERRED 0.85]
- **Observer Ephemeris Configuration for Mars** — doc_media_image3_ephemeris_type_observer, doc_media_image3_target_body_mars_499, doc_media_image3_observer_location_geocentric_500, doc_media_image3_time_span, doc_media_image3_generate_ephemeris_button [EXTRACTED 1.00]
- **Ephemeris computation time window (start, stop, step-size)** — doc_media_image4_start_time, doc_media_image4_stop_time, doc_media_image4_step_size [EXTRACTED 1.00]
- **SSOE Ephemeris Output Block (command, coordinate frame, table format)** — doc_media_image5_ssaoe_command, doc_media_image5_icrf_j20000_frame, doc_media_image5_ephemeris_table_format [EXTRACTED 1.00]
- **Ephem Table Layout: Date(UT) + R.A.(ICRF) + DEC columns** — doc_media_image7_date_ut_column, doc_media_image7_ra_icrf, doc_media_image7_dec_column, doc_media_image7_ephem_rows [EXTRACTED 1.00]
- **Ephemeris Record Structure: TT Date + R.A.(ICRF) + DEC per Day** — doc_media_image10_tt_date_header, doc_media_image10_ra_icrf_column, doc_media_image10_dec_column [EXTRACTED 1.00]
- **Dialog legend: per-quantity symbol modifiers** — doc_media_image11_observer_quantities_dialog, doc_media_image11_atmospheric_refraction, doc_media_image11_orbit_covariance [EXTRACTED 1.00]
- **Ephemeris Output Columns: TT Date, ICRF Airless-Apparent RA, Dec** — doc_media_image12_image, concept_tt_time_scale, concept_icrf_airless_apparent_coordinates [EXTRACTED 1.00]
- **Settings dialog composition: quantity groups, legend notes, and HORIZONS reference** — doc_media_image13_observer_quantities_dialog, doc_media_image13_astro_quantities, doc_media_image13_orbital_stat_quantities, doc_media_image13_refraction_covariance_note, doc_media_image13_horizons_documentation [EXTRACTED 1.00]
- **Swiss Ephemeris Ephemmeris Table: Sun coordinates over 3 consecutive daily epochs** — doc_media_image14_sun_ephemeris_table, doc_media_image14_ra_dec_columns, doc_media_image14_obs_ecl_lon_lat, doc_media_image14_tt_datetime, doc_media_image14_sose_object [EXTRACTED 1.00]
- **Ephemeris Calculation Configuration (Current Settings panel group)** — doc_media_image15_ephemeris_type, doc_media_image15_target_body, doc_media_image15_observer_location, doc_media_image15_time_span, doc_media_image15_table_settings, doc_media_image15_display_output [EXTRACTED 1.00]
- **Swiss Ephemeris Observation Output Coordinate Columns (Sidereal Time, Apparent RA/DEC, Observed Ecliptic)** — doc_media_image16_sideral_time, doc_media_image16_apparent_equatorial, doc_media_image16_obs_ecliptic, doc_media_image16_ssoe [EXTRACTED 1.00]
- **Definition of airless apparent equatorial coordinate system with apparent corrections** — doc_media_image17_image, doc_media_image17_airless_apparent_ra_dec, doc_media_image17_apparent_coordinate_corrections [EXTRACTED 1.00]
- **Corrections composing the ObsEclLon/ObsEclLat apparent position** — doc_media_image18_obsecllon_obsecllat, doc_media_image18_lighttime_correction, doc_media_image18_gravitational_deflection, doc_media_image18_stellar_aberration [EXTRACTED 1.00]
- **Swisseph Sample Output: Sidereal Time plus Apparent Topocentric and Observer Ecliptic Coordinates** — doc_media_image19_sample_output_table, doc_media_image19_sidereal_time_column, doc_media_image19_apparent_ra_dec_column, doc_media_image19_obs_ecliptic_coords_column, doc_media_image19_observed_dates_row [EXTRACTED 1.00]
- **HORIZONS Observer-Mode Query Page: Current Settings and Time Span Form** — doc_media_image20_horizons_query_page, doc_media_image20_ephemeris_type_observer, doc_media_image20_target_body_sol_10, doc_media_image20_observer_geocentric_500, doc_media_image20_time_span_form, doc_media_image20_tt_time_span_range [EXTRACTED 1.00]
- **Swiss Ephemeris Web UI configuration interface (settings panel + target body lookup)** — doc_media_image22_swisseph_webui_current_settings_panel, doc_media_image22_target_body_search_form, doc_media_image22_ephemeris_parameters_configuration [EXTRACTED 1.00]
- **Ephemeris Table: TT Date plus Apparent Equatorial and Ecliptic-Observer Columns per Day at 00:00** — doc_media_image25, doc_media_image25_date_tt, doc_media_image25_ra_airls_apparent, doc_media_image25_dec, doc_media_image25_obsec_lon, doc_media_image25_obsec_lat [EXTRACTED 1.00]
- **Current Settings Panel Fields** — doc_media_image26_current_settings_panel, doc_media_image26_ephemeris_type_observer, doc_media_image26_target_body_io, doc_media_image26_observer_location_geocentric, doc_media_image26_time_span, doc_media_image26_table_settings, doc_media_image26_display_output_html [EXTRACTED 1.00]
- **Ephemeris Target Body Change Flow - Current Settings panel with change link opens the Target Body selection dialog** — doc_media_image23_current_settings, doc_media_image23_target_body_dialog [EXTRACTED 1.00]
- **SEPM ephemeris file structure: SWISSEPH 1 header, sepm9501.sel filename, Astrodienst copyright line, and object record line for Io/Jupiter** — doc_media_image29, doc_media_image29_sepm9501_header_format, doc_media_image29_www_user_record_line [EXTRACTED 1.00]
- **Indian Calendar ayanamṣa pipeline: initial ecliptic point → mean ayanamṣa formula → nirayana longitudes → rāśi/nakṣatra** — doc_media_image36_indian_calendar_part, doc_media_image36_ayanamsa, doc_media_image36_ayanamsa_formula, doc_media_image36_nirayana_longitude, doc_media_image36_rasi_nakshatra [EXTRACTED 1.00]
- **Ayanāṃśa definition: True Ayanāṃśa = Mean Ayanāṃśa + Nutation in longitude** — doc_media_image37_true_ayanamsa, doc_media_image37_mean_ayanamsa, doc_media_image37_nutation_in_longitude [EXTRACTED 1.00]
- **Reformed Calendar of India - daily table columns (Date, Sunrise/Set, Tithi, Nakshatra, Transits, Phenomena, Festivals)** — doc_media_image38_reformed_calendar_of_india, doc_media_image38_caitra_month, doc_media_image38_shaka_era_1878, doc_media_image38_tithi, doc_media_image38_nakshatra, doc_media_image38_punarvasu, doc_media_image38_indian_new_years_day [EXTRACTED 1.00]
- **Current Settings panel fields (observer ephemeris of Io from Jupiter)** — doc_media_image30_current_settings_panel, doc_media_image30_ephemeris_type_observer, doc_media_image30_target_body_io, doc_media_image30_observer_location_jupiter, doc_media_image30_time_span, doc_media_image30_table_settings, doc_media_image30_display_output [EXTRACTED 1.00]

## Communities (114 total, 30 thin omitted)

### Community 0 - "Android JNI Export Layer"
Cohesion: 0.11
Nodes (111): appendToBuilder(), emptyBuilder(), getBuilderString(), Java_swisseph_SwephExp_swe_1azalt(), Java_swisseph_SwephExp_swe_1azalt_1rev(), Java_swisseph_SwephExp_swe_1calc(), Java_swisseph_SwephExp_swe_1calc_1pctr(), Java_swisseph_SwephExp_swe_1calc_1ut() (+103 more)

### Community 1 - "Date, Time & Leap-Second Core"
Cohesion: 0.05
Nodes (68): seleapsec.txt (Android JNI Copy), seleapsec.txt Leap Second Dates, init_leapsec(), swe_date_conversion(), swe_jdet_to_utc(), swe_jdut1_to_utc(), swe_julday(), swe_revjul() (+60 more)

### Community 2 - "Android JNI Core (swecl)"
Cohesion: 0.09
Nodes (79): calc_astronomical_refr(), calc_dip(), calc_mer_trans(), calc_planet_star(), eclipse_how(), eclipse_when_loc(), eclipse_where(), find_maximum() (+71 more)

### Community 3 - "Nutation & Ayanamsha (JNI)"
Cohesion: 0.06
Nodes (58): CSEC, nut_matrix(), swe_get_ayanamsa(), swe_get_ayanamsa_ut(), swi_check_nutation(), adjust_for_tidacc(), bessel(), calc_deltat() (+50 more)

### Community 4 - "Astronomical Phenomena Helpers (JNI)"
Cohesion: 0.10
Nodes (57): Airmass(), AppAltfromTopoAlt(), Bcity(), Bday(), Bm(), Bn(), Bsky(), Btwi() (+49 more)

### Community 5 - "JPL Horizons Validation Suite"
Cohesion: 0.06
Nodes (48): Test 2: Inertial Apparent Positions (RA/DE in ICRF) and ObsEcLon/ObsEcLat comparison against JPL Horizons, JPL Horizons output table: SSO apparent RA & DE (airless=apparent) with ObsEcLon/ObsEcLat, 25-27 Oct 2016, JPL Horizons 'Current Settings' Panel Screenshot (Ephemeris Type: OBSERVER, Target Body: Venus [299], Observer Location: Jerusalem Israel, Time Span: 2015-09-01 05:00 TT, Table Settings QUANTITIES=2,31 extra precision=YES, Display/Output default HTML, with Generate Ephemeris button), Swiss Ephemeris Professional License, Body numbers (int ipl) in swephexp.h, Date/time and Delta T functions (9, 10), swe_deltat() / swe_deltat_ex(), Fixed star functions (swe_fixstar, swe_fixstar_ut, swe_fixstar2, swe_fixstar_mag) (+40 more)

### Community 6 - "Phenomena & Azimuth/Altitude Engine"
Cohesion: 0.15
Nodes (48): swe_pheno_ut(), azalt_cart(), int32, call_swe_calc(), call_swe_fixstar(), call_swe_fixstar_mag(), call_swe_rise_trans(), crossing() (+40 more)

### Community 7 - "Orbital Elements & Sidereal Houses"
Cohesion: 0.18
Nodes (47): swe_get_orbital_elements(), swe_nod_aps(), sidereal_houses_ecl_t0(), sidereal_houses_ssypl(), ecldat_equ2000(), swi_mean_apog(), embofs_mosh(), swi_osc_el_plan() (+39 more)

### Community 8 - "graphify Tooling & Exports"
Cohesion: 0.07
Nodes (45): graphify Trigger (.claude/CLAUDE.md), graphify Reference: add URL and watch, /graphify add — URL Ingest, --watch Folder Watcher, graphify Reference: Extra Exports and Benchmark, Token-Reduction Benchmark (Step 8), FalkorDB Export (--falkordb / --falkordb-push), MCP Server (--mcp, graphify.serve) (+37 more)

### Community 9 - "Planetary Theory (JNI)"
Cohesion: 0.20
Nodes (43): swe_nod_aps(), sidereal_houses_ecl_t0(), sidereal_houses_ssypl(), ecldat_equ2000(), embofs_mosh(), swi_osc_el_plan(), app_pos_etc_mean(), app_pos_etc_plan_osc() (+35 more)

### Community 10 - "Fixed-Star Catalog Engine (JNI)"
Cohesion: 0.13
Nodes (40): aberr_light(), calc_center_body(), embofs(), fixstar_cut_string(), fixstar_format_search_name(), get_builtin_star(), load_all_fixed_stars(), meff() (+32 more)

### Community 11 - "Fixed-Star & Orbital Data Files"
Cohesion: 0.10
Nodes (39): sefstars.txt Fixed Stars Data File, SEFSTARS Record Format (names, ICRS position, proper motion, parallax, magnitude), int32, check_t_terms(), read_elements_file(), swi_get_fict_name(), aberr_light(), calc_center_body() (+31 more)

### Community 12 - "Events Engine (swevents)"
Cohesion: 0.11
Nodes (40): EVENT, main(), swe_get_planet_name(), trace_swe_get_planet_name(), swe_deltat(), AS_BOOL, FILE, int32 (+32 more)

### Community 13 - "Nutation & Delta-T Library"
Cohesion: 0.09
Nodes (37): adjust_for_tidacc(), bessel(), calc_deltat(), calc_nutation(), calc_nutation_iau1980(), calc_nutation_iau2000ab(), calc_nutation_woolard(), deltat_aa() (+29 more)

### Community 14 - "Windows GUI (Swisseph for Windows)"
Cohesion: 0.09
Nodes (34): DLGPROC, LPARAM, about_proc(), atoslng(), atoulng(), HWND, int32, LONG (+26 more)

### Community 15 - "Core Library (sweph/swecl)"
Cohesion: 0.19
Nodes (36): calc_astronomical_refr(), calc_dip(), calc_mer_trans(), calc_planet_star(), eclipse_how(), eclipse_when_loc(), eclipse_where(), find_maximum() (+28 more)

### Community 16 - "Ephemeris Data Files & Test Cases"
Cohesion: 0.09
Nodes (33): seorbel.txt (Android JNI Copy), astlistn.md Asteroid List, plmolist.txt Planetary Moon Numbers and Body Centers, seasnam.txt Asteroid Names File, seorbel.txt Fictitious Planets Orbital Elements, Fictitious Planet Orbital Elements Format, constants.c SEFLG Definitions, globals_suite.c Test Result Checkers (+25 more)

### Community 17 - "setest Multi-Value Reader"
Cohesion: 0.15
Nodes (31): multivalues_all_done(), multivalues_clear(), rdr_ctx, t_section, test_context, cleanup(), close_testcase(), close_testsuite() (+23 more)

### Community 18 - "swetest Test Driver & Calls"
Cohesion: 0.21
Nodes (31): swe_revjul(), swe_split_deg(), AS_BOOL, int32, call_heliacal_event(), call_lunar_eclipse(), call_lunar_occultation(), call_rise_set() (+23 more)

### Community 19 - "Phenomena Helper Functions (swehel)"
Cohesion: 0.13
Nodes (30): Airmass(), AppAltfromTopoAlt(), Bcity(), Bday(), Bm(), Bn(), Bsky(), Btwi() (+22 more)

### Community 20 - "setest Checkpoint Framework"
Cohesion: 0.18
Nodes (27): failure, failures, pair, test_context, typed_value, check_d(), check_d_internal(), check_dd() (+19 more)

### Community 21 - "Gauquelin & Ascension Sectors"
Cohesion: 0.19
Nodes (25): swe_gauquelin_sector(), apc_sector(), armc_to_mc(), Asc1(), Asc2(), AscDash(), CalcH(), fix_asc_polar() (+17 more)

### Community 22 - "House Systems & Library I/O"
Cohesion: 0.14
Nodes (26): swe_houses_ex(), swe_houses_ex2(), do_fread(), free_planets(), get_new_segment(), read_const(), swe_close(), swe_get_ayanamsa_name() (+18 more)

### Community 23 - "JPL Ephemeris (swejpl)"
Cohesion: 0.19
Nodes (25): swi_close_jpl_file(), swi_pleph(), AS_BOOL, swi_moshmoon(), AS_BOOL, swi_moshplan(), app_pos_etc_moon(), app_pos_etc_plan() (+17 more)

### Community 24 - "JPL Ephemeris (JNI)"
Cohesion: 0.22
Nodes (24): swi_close_jpl_file(), swi_pleph(), swi_moshmoon(), swi_moshplan(), app_pos_etc_moon(), app_pos_etc_plan(), app_pos_etc_sbar(), app_pos_etc_sun() (+16 more)

### Community 25 - "Moshier JPL Format Reader"
Cohesion: 0.17
Nodes (19): AS_BOOL, centisec, dephread2(), eph4_posit(), ephe4_unpack(), ephe4_unpack_d(), ephe_plac2swe(), ephread() (+11 more)

### Community 26 - "setest Test Suites"
Cohesion: 0.13
Nodes (6): test_context, check_swecalc_results(), check_swehouses_armc_ex2_results(), check_swehouses_armc_results(), check_swehouses_ex2_results(), check_swehouses_results()

### Community 27 - "setest Test-Data Parsers"
Cohesion: 0.24
Nodes (17): entry, st_type, is_multivalue(), FILE, pair, st_type, test_context, typed_value (+9 more)

### Community 28 - "setest Config Reader"
Cohesion: 0.25
Nodes (17): is_empty(), FILE, rdr_ctx, t_section, clear_table(), close_reader(), find_value(), open_reader() (+9 more)

### Community 29 - "Library I/O & File Management (JNI)"
Cohesion: 0.18
Nodes (17): do_fread(), free_planets(), get_new_segment(), read_const(), swe_close(), swe_set_ephe_path(), swe_set_jpl_file(), swi_close_keep_topo_etc() (+9 more)

### Community 30 - "Rise/Set & Magnitudes (JNI)"
Cohesion: 0.24
Nodes (16): calc_rise_and_set(), call_swe_fixstar_mag(), call_swe_rise_trans(), DeterObject(), fast_magnitude(), find_conjunct_sun(), get_heliacal_day(), get_heliacal_details() (+8 more)

### Community 31 - "Acronychal & Ascension (JNI)"
Cohesion: 0.17
Nodes (15): azalt_cart(), call_swe_fixstar(), get_asc_obl(), get_asc_obl_acronychal(), get_asc_obl_diff(), get_asc_obl_diff_old(), get_asc_obl_old(), get_asc_obl_with_sun() (+7 more)

### Community 32 - "setest Value-Table Matchers"
Cohesion: 0.28
Nodes (14): mvalues, mvalues_tab, equals(), add_double_to_table(), add_int_to_table(), add_value_to_table(), typed_value, multivalues_add_index() (+6 more)

### Community 33 - "setest Utilities (globals)"
Cohesion: 0.19
Nodes (5): ends_with(), is_blank(), trim_space(), trim_trailing_space(), trimmed_equals()

### Community 34 - "Licensing & Contrib Overview"
Cohesion: 0.22
Nodes (10): GNU AGPL Version 3 Full License Text, sefstars.txt (Android JNI Copy), swe-jni-lib Android JNI Interface (Yuriy Krymlov), contrib/ Directory of Free Contributions to Swiss Ephemeris, Swiss Ephemeris Documentation Folder (doc/), SE1 Compressed Ephemeris Data Files (.se1), GNU Affero General Public License (referenced), Swiss Ephemeris Professional License (+2 more)

### Community 35 - "Fictitious Planets & Elements (JNI)"
Cohesion: 0.27
Nodes (10): check_t_terms(), read_elements_file(), sscc(), swi_get_fict_name(), swi_moshplan2(), load_dpsi_deps(), swi_fopen(), init_dt() (+2 more)

### Community 36 - "Coordinate System Utilities (JNI)"
Cohesion: 0.33
Nodes (9): swe_csnorm(), swe_csroundsec(), swe_difcs2n(), swe_difcsn(), centisec, swe_csnorm(), swe_csroundsec(), swe_difcs2n() (+1 more)

### Community 37 - "HORIZONS Observer Settings UI"
Cohesion: 0.43
Nodes (8): Ephemeris Type Setting: OBSERVER, Link to HORIZONS Documentation for Accepted Time Formats, JPL HORIZONS Query Page Screenshot (Observer Mode, TT Time Span), Observer Location: Geocentric [500], Target Body: Sun [Sol] [10], Time Format Specification (calendar dates, UT/TT/TTD, Julian dates, AD/BC rules), Time Span Form (10/30/60-day Presets, Start/Stop Time, Step Size), TT Time Span: 9901BC-01-02 TT to 9901BC-01-02, Step 1 d

### Community 38 - "Indian Panchang (Saka Era) Table"
Cohesion: 0.36
Nodes (8): Ayanamsha on 1st = 23 deg 15 min 0 sec; Mega: Madhava, Month of Caitra (Spring 2nd Month, 31 Days, Leap-year), 1-Indian New Year's Day (festival on 21 Mar 1956), Nakshatra (lunar mansion) column with number, name and ending moment, Punarvasu nakshatra (No. 7, ending 21:16 h:m on 21 Mar 1956), Reformed Calendar of India - Caitra Month Table (Saka Era 1878, 1956-57 A.D., leap year), Saka Era 1878 (1956-57 A.D.), Tithi (lunar day) column with number and ending moment

### Community 39 - "HORIZONS Settings Panel (Geocentric)"
Cohesion: 0.43
Nodes (7): Current Settings Panel (Ephemeris GUI Screenshot), Display/Output: default (formatted HTML), Ephemeris Type Setting: OBSERVER, Observer Location: Sun (barycenter) 500@10, Table Settings: QUANTITIES=2,31, extra precision=YES, Target Body: Mars Barycenter [4], Time Span: Start 2016-10-25 00:00 TT, Stop 2016-11-10, Step 1 d

### Community 40 - "HORIZONS Settings (Geocentric #2)"
Cohesion: 0.38
Nodes (7): Current Settings Panel (Ephemeris Tool UI), Display/Output: default (formatted HTML), Ephemeris Type = OBSERVER, Observer Location: Geocentric [500], Table Settings: QUANTITIES=31, extra precision=YES, Target Body: Io (JII) [501], Time Span: Start=2016-10-25 00:00 TT, Stop=2016-11-10, Step=1 d

### Community 41 - "HORIZONS Settings (Geocentric #3)"
Cohesion: 0.38
Nodes (7): Current Settings Panel Screenshot (Ephemeris Tool), Current Settings Panel, Ephemeris Type: OBSERVER, Generate Ephemeris Button, Observer Location: Geocentric [500], Target Body: Mars [499], Time Span (Start 2016-10-25, Stop 2016-11-24, Step 1 d)

### Community 42 - "HORIZONS Settings (Jupiter Barycenter)"
Cohesion: 0.38
Nodes (7): Current Settings Panel (Ephemeris Calculator UI), Display/Output Setting = default (formatted HTML), Ephemeris Type Setting = OBSERVER, Observer Location Setting = Jupiter (body center) [500@559], Table Settings (QUANTITIES=31, extra precision=YES), Target Body Setting = Io (JII) [501], Time Span Setting (Start 2016-10-25 TT, Stop 2016-11-10, Step 1 d)

### Community 43 - "Orbital Extremum Search"
Cohesion: 0.57
Nodes (7): get_dist_from_2_vectors(), orbit_max_min_true_distance_helio(), osc_get_ecl_pos(), osc_get_orbit_constants(), osc_iterate_max_dist(), osc_iterate_min_dist(), swe_orbit_max_min_true_distance()

### Community 44 - "Apparent-Position Output (Image 10)"
Cohesion: 0.47
Nodes (6): Daily Ephemeris Rows (2016-Oct-25 to 2016-Oct-28, 00:00), DEC Column, Ephemeris Output Listing ($SOE Sample), R.A. (ICRF) Column, $SOE Header Marker, Date (TT) __HR:MIN Column Header

### Community 45 - "Light-Time & Deflection Corrections"
Cohesion: 0.60
Nodes (6): Gravitational deflection of light correction, Documentation screenshot defining ObsEclLon/ObsEclLat, J2000 standard epoch (IAU76/80), Light-time correction applied to apparent position, ObsEclLon/ObsEclLat - target center apparent ecliptic position for non-Earth observer, Stellar aberration correction

### Community 46 - "Apparent Output (Topocentric, image19)"
Cohesion: 0.47
Nodes (6): R.A. (airs-apparent) and DEC Columns — apparent topocentric coordinates in degrees, minutes, seconds, ObsEclon / ObsEclat Columns — observer's ecliptic longitude and latitude in decimal degrees, Sample Rows: Oct-25/26/27 1800 at 00:00 TT, Sample Output Table: Sidereal Time, Apparent (airs) RA/DEC, and Observer Ecliptic Coordinates, Sidereal Time (Tt) Column — Date, (Tt), HR:MN, $SSOE Output Section Marker

### Community 47 - "Output Table (ObsEcLon/ObsEcLat)"
Cohesion: 0.40
Nodes (6): Ephemeris Data Table Screenshot (Date TT, R.A. airless-apparent, DEC, ObsEcLon, ObsEcLat), Date_(TT)_HR:MN Column - Terrestrial Time Date and Time of Ephemeris Entries, DEC Column - Declination (D:M:S format), ObsEcLat Column - Observer Ecliptic Latitude (decimal degrees), ObsEcLon Column - Observer Ecliptic Longitude (decimal degrees), R.A.__(airls-apparent)__ Column - Airless-Apparent Right Ascension (H:M:S format)

### Community 48 - "Indian Calendar: Ayanamsha (Part V)"
Cohesion: 0.40
Nodes (6): Page 474 — Explanation, Part V: Indian Calendar (swisseph manual page image), Ayanamṣa (mean ayanamṣa) — fixed initial point on the ecliptic, tropical longitude 23°15' 0".0 on March 21, 1956, Mean ayanamṣa formula: A = 22°27'37".69 + 5025".64T + 1".11T² (T in tropical centuries from 1900.0) or A = 22°27'37".65 + 5025".75T + 1".11T² (T in centuries of 36525 ephemeris days from 1900.0), Part V — Indian Calendar section of the Explanation, Nirayana (siddhāntic) longitudes — obtained by subtracting the mean ayanamṣa from tropical (sāyana) longitudes of celestial objects, Rāśi and nakṣatra longitude calculations for the Central Station of India (82°30' E. Long., 23°11' N. Lat.)

### Community 49 - "Ayanamsha & Nutation API"
Cohesion: 0.33
Nodes (6): nut_matrix(), swe_get_ayanamsa_ex(), swe_get_ayanamsa_ex_ut(), swi_check_nutation(), quadratic_intp(), swi_nutation()

### Community 50 - "HORIZONS Observer Quantities Dialog"
Cohesion: 0.60
Nodes (5): Astrometric & Geometric Observer Quantities (items 1-30), HORIZONS Documentation (linked reference for observer quantities), Observer Quantities Selection Dialog (Settings Checkboxes), Orbital & Statistical Observer Quantities (items 31-43), Dialog Notes: Atmospheric Refraction Setting & Orbit-Covariance Statistical Values

### Community 51 - "Sun Ephemeris Table (image14)"
Cohesion: 0.60
Nodes (5): Observed Geocentric Ecliptic Longitude and Latitude Columns, R.A. and DEC Columns (airless apparent geocentric coordinates), SOSOE Solar System Object (Sun) Entry, 2016 Oct 25-27, Sun Ephemmeris Output Table (image14.png), TT (Terrestrial Time) Date-Hour-Minute Column

### Community 52 - "Sun Ephemeris Output (image16)"
Cohesion: 0.50
Nodes (5): Swiss Ephemeris Observation Output Table (Sun $SSOE, 2016-10-25 to 2016-10-27), Airless-Apparent RA/DEC (Topocentric Equatorial) Column, Observed Geocentric Ecliptic Longitude/Latitude (ObsEclLon/ObsEclLat) Column, Geocentric Sidereal Time (TT) Column, $SSOE Sun Ephemeris Rows

### Community 53 - "HORIZONS Target-Body Selection"
Cohesion: 0.60
Nodes (5): Documentation Screenshot - Ephemeris Current Settings Panel and Target Body Selection Dialog, Swiss Ephemeris Body Identifier Numbering - bracketed IDs such as Mars [499] and Geocentric [500], Current Settings Panel (Ephem Type OBSERVER, Target Body Mars [499], Observer Location Geocentric [500], Time Span 1800-10-25 to 1800-11-24 Step 1 d, QUANTITIES=2.31, Display/Output default formatted HTML), Table Settings QUANTITIES=2.31 with extra precision=YES and default formatted HTML output, Target Body Selection Dialog - select from matching bodies (Jupiter Barycenter, Jupiter) with Select Indicated Body / Cancel buttons

### Community 54 - "Ayanamsha & Nutation-in-Longitude"
Cohesion: 0.50
Nodes (5): Image: Ayanāṃśa longitude values with precession from reference epochs 1950.0, 1973.0, 1974.0 and definition Ayanāṃśa = Mean Ayanāṃśa + Nutation in longitude, Mean Ayanāṃśa (mean ayanamsa, listed at reference epochs 1950.0, 1973.0, 1974.0 with precession in longitude to date), Nutation in longitude added to mean ayanāṃśa to obtain true ayanāṃśa, Precession in longitude applied to aynāṃśa values from reference epochs to date, True Ayanāṃśa (Ayanāṃśa = Mean Ayanāṃśa + Nutation in longitude)

### Community 55 - "Ephemeris Time-Range Parameters"
Cohesion: 0.50
Nodes (5): Screenshot: Ephemeris run time parameters (start/stop time, step-size), Daily ephemeris sampling (one position per day = 1440-minute step), Start time A.D. 2016-Oct-25 00:00:00.0000 UT, Step-size 1440 minutes, Stop time A.D. 2016-Nov-24 00:00:00.0000 UT

### Community 56 - "Ephem Table Output (ICRF, image7)"
Cohesion: 0.80
Nodes (5): Terminal Screenshot: Ephem Table Output (Date UT, R.A. ICRF, DEC), Date (UT) / HR:MN Column, e.g. 2016-Oct-25 00:00, Declination Column (DD MM SS, negative for south), Ephemeris Rows for Object $SOE (2016-Oct-25..27, daily 00:00 UT), Right Ascension Column in ICRF Reference Frame

### Community 57 - "Apparent Output (Airless, image12)"
Cohesion: 0.83
Nodes (4): ICRF Airless-Apparent Coordinates (RA/DEC without atmospheric refraction), SSOE Ephemeris Table (daily 00:00 solar system object positions), TT (Terrestrial Time) Time Scale, Astronomical Ephemeris Table Image (Date TT, ICRF Airless-Apparent RA/DEC)

### Community 58 - "Atmospheric Refraction Option"
Cohesion: 0.67
Nodes (4): Optional Atmospheric Refraction Setting, HORIZONS Documentation, HORIZONS Observer Output Quantities Settings Dialog, Orbit Covariance (statistical value source)

### Community 59 - "$SOE Output Table (image31)"
Cohesion: 0.67
Nodes (4): ObsEcLat - observed ecliptic latitude column (degrees, e.g. -1.0216307 on 2016-Oct-25), ObsEcLon - observed ecliptic longitude column (degrees, e.g. 185.5872616 on 2016-Oct-25), $SOE ephemeris section marker line, Sample table of daily observed ecliptic coordinates with $SOE marker (2016-Oct-25..27)

### Community 60 - "$SSOE Ephemeris Output (image5)"
Cohesion: 0.67
Nodes (4): Ephemeris Table Output Sample (SSOE command, Oct 2016), Ephemeris Table Row Format (Date UT / R.A. / Dec / APO), ICRF/J2000.0 Equatorial Coordinate Reference Frame, $SSOE Ephemeris Query Command

### Community 61 - "Airless-Apparent Coordinate Definition"
Cohesion: 0.67
Nodes (3): Airless apparent equatorial coordinates (R.A. & DEC) relative to IAU 2009 equator and ICRF meridian, Apparent coordinate corrections: light-time, gravitational deflection of light, stellar aberration, IAU spin axis, Documentation image: R.A.__(airless-apparent)__DEC definition

### Community 62 - "HORIZONS Target Search (Mars)"
Cohesion: 1.00
Nodes (3): Ephemeris Parameters Configuration (Ephemeris Type, Target Body [499], Observer Location, Time Span, Table Settings QUANTITIES=2.51 extra precision, Display/Output), Swiss Ephemeris Web UI - Current Settings Panel Screenshot, Target Body Search Form (lookup of specified body, e.g. Jupiter, all-bodies dropdown, Search button)

### Community 63 - "SEPM Ephemeris File Header (Io)"
Cohesion: 1.00
Nodes (3): Terminal screenshot showing header of SEPM ephemeris file sepm9501.sel, SEPM .sel ephemeris file header format (SWISSEPH version line, filename, copyright, object record line), Ephemeris object record line with object code 009501 Io/Jupiter, user field WWW USER, generation date and location Pasadena USA

### Community 64 - "Lahiri Ayanamsha (Rashtriya Panchang)"
Cohesion: 1.00
Nodes (3): Rashtriya Panchang 2019 excerpt (1st Caitra, 22 March 2019, ayanamsha 24°07'16"), Appendix E of Swiss Ephemeris documentation: reproducing ayanamsha values from IAEA/IENA/Rashtriya Panchang, Lahiri (ICRC) ayanamsha definition and SE_SIDM_LAHIRI / SE_SIDM_LAHIRI_ICRC sids

### Community 65 - "Extra-Precision Output Option"
Cohesion: 0.67
Nodes (3): Extra precision option (additional digits for RA/Dec quantities), UI Screenshot: extra precision checkbox, RA/Dec output precision (extra digits for right ascension/declination display)

### Community 66 - "Astrological House Systems (6.x)"
Cohesion: 0.67
Nodes (3): House cusps beyond the polar circle (6.4), House position and Gauquelin sector position of a planet (6.5, 6.6), Astrological house systems (6.2)

## Ambiguous Edges - Review These
- `Optional Atmospheric Refraction Setting` → `Orbit Covariance (statistical value source)`  [AMBIGUOUS]
  doc/media/image11.png · relation: conceptually_related_to
- `Sample Output Table: Sidereal Time, Apparent (airs) RA/DEC, and Observer Ecliptic Coordinates` → `$SSOE Output Section Marker`  [AMBIGUOUS]
  doc/media/image19.png · relation: conceptually_related_to

## Knowledge Gaps
- **95 isolated node(s):** `test.sh script`, `test_mytest_ok.sh script`, `test_read_section.sh script`, `Interpreter Guard (.graphify_python)`, `Hyperedge Rule (max 3 per chunk)` (+90 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 174 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **30 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Optional Atmospheric Refraction Setting` and `Orbit Covariance (statistical value source)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Sample Output Table: Sidereal Time, Apparent (airs) RA/DEC, and Observer Ecliptic Coordinates` and `$SSOE Output Section Marker`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `swe_calc()` connect `Ephemeris Data Files & Test Cases` to `Licensing & Contrib Overview`, `Phenomena & Azimuth/Altitude Engine`, `Orbital Elements & Sidereal Houses`, `Fixed-Star Catalog Engine (JNI)`, `Fixed-Star & Orbital Data Files`, `Events Engine (swevents)`, `Core Library (sweph/swecl)`, `swetest Test Driver & Calls`, `Gauquelin & Ascension Sectors`, `House Systems & Library I/O`, `JPL Ephemeris (swejpl)`, `Moshier JPL Format Reader`, `Acronychal & Ascension (JNI)`?**
  _High betweenness centrality (0.043) - this node is a cross-community bridge._
- **Why does `Swiss Ephemeris Main README` connect `Licensing & Contrib Overview` to `Ephemeris Data Files & Test Cases`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Why does `SE1 Compressed Ephemeris Data Files (.se1)` connect `Licensing & Contrib Overview` to `Ephemeris Data Files & Test Cases`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **What connects `test.sh script`, `test_mytest_ok.sh script`, `test_read_section.sh script` to the rest of the system?**
  _95 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Android JNI Export Layer` be split into smaller, more focused modules?**
  _Cohesion score 0.10714285714285714 - nodes in this community are weakly interconnected._