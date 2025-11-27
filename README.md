# script-for-netlist
Automated script that detects library netlist types and auto-runs Cadence Tempus timing analysis.
Auto Netlist Detection: Identifies Liberty (.lib) library netlist types automatically
- Seamless Tempus Integration: Launches Cadence Tempus timing analysis without manual intervention
- Multi-Format Support: Handles various netlist formats and configurations
- Comprehensive Logging: Detailed execution logs and analysis reports

git clone https://github.com/kirankpatil2005-create/script-for-netlist
cd script-for-netlist
Make scripts executable

chmod +x scripts/Auto_library

## ⚙️ Configuration

Critical Step: Update the `LIB_PATHS` dictionary in the main Python script with your actual Liberty file paths:

LIB_PATHS = {
"RAK": "/path/to/your/RAK/slow.lib",
"NANGATE": "/path/to/your/NangateOpenCellLibrary_slow_ccs.lib",
"Skywater": "/path/to/your/sky130_fd_sc_ms/slow.lib",
"rf_2p_136d_74w_1m_4b": "/path/to/your/rf_2p_136d_74w_1m_4b.lib",
"rf_2p_256d_76w_1m_4b": "/path/to/your/rf_2p_256d_76w_1m_4b.lib",
"rf_2p_512d_76w_2m_4b": "/path/to/your/rf_2p_512d_76w_2m_4b.lib",
"sram_sp_512d_32w_4m_2b": "/path/to/your/sram_sp_512d_32w_4m_2b.lib",
"sram_sp_16384d_36w_16m_8b": "/path/to/your/sram_sp_16384d_36w_16m_8b.lib",
"sram_sp_32768d_33w_16m_8b": "/path/to/your/sram_sp_32768d_33w_16m_8b.lib"
}

