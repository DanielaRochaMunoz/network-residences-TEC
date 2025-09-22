# Network Design & Implementation — TEC Residences

Network infrastructure project for university residences, focused on full coverage, efficiency, and complete technical documentation.

## Main Features
- Physical and logical network topology designed for residential environments.
- Cabling maps and Access Point (AP) placement.
- Simulation in Cisco Packet Tracer to validate connectivity and performance.
- Complete technical documentation: diagrams, configurations, addressing tables.

## Results & Impact
- Optimized network coverage for a university residential building.
- Design validated before real implementation.
- Clear and replicable documentation for IT teams.

## Tech Stack
- **Simulation:** Cisco Packet Tracer  
- **Protocols:** TCP/IP, DHCP, NAT, VLANs, Routing  
- **Design Tools:** Network diagrams, cabling plans  

## Installation & Execution
### Clone repository
```bash
git clone <repo-red-tec>
cd repo-red-tec
```

### Open project in Cisco Packet Tracer
- Download and install Cisco Packet Tracer.  
- Open the main project file:  
  `red_residencias_tec.pkt`

### Validate configuration
- Review IP address assignment on switches and routers.  
- Test connectivity between simulated clients and servers (`ping`, `tracert`).  
- Validate DHCP and NAT operation.  

## Repository Structure
```
/residencias-tec-network
 ├── red_residencias_tec.pkt     # Main Packet Tracer project
 ├── /docs
 │    ├── topologia_fisica.pdf   # Physical topology
 │    ├── topologia_logica.pdf   # Logical topology
 │    ├── direccionamiento.csv   # IP addressing table
 │    └── configuraciones.txt    # Device configurations
 └── README.md
```

## Best Practices Applied
- Standardized documentation for maintainability.  
- VLANs for traffic segmentation.  
- DHCP for dynamic IP assignment.  
- NAT for controlled Internet access.  
