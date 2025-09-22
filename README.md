# 📘 CMDB Dashboard Scripts for ServiceNow

Welcome to the **CMDB Dashboard Scripts** repository - a curated set of ServiceNow Jelly scripts designed to help you build clean, dynamic, and insightful dashboards using data from your Configuration Management Database (CMDB).

These scripts are optimized for use in **Content Blocks**, **UI Macros**, or **Service Portal Widgets**, and focus on surfacing key relationships, classifications, and infrastructure breakdowns in a visually intuitive format.

---

## 🎯 Purpose

The CMDB is a powerful source of truth, but its value is only realized when data is made **accessible**, **actionable**, and **understandable**. 

- Visualize relationships between services and infrastructure components  
- Summarize service classifications and offerings  
- Map network paths and dependencies  
- Break down server inventories by platform  
- Build modular, reusable UI components for dashboards  

---

## 📦 What's Included

### 🔗 Relationship Scripts

These scripts highlight CMDB relationships between services and infrastructure:

- Applications → Servers  
- Technical Services → Servers  
- Services → Network Devices  
- Services → Mainframes  
- Services → Storage Devices  

### 🧮 Service Classification Scripts

These scripts provide counts and summaries of service types:

- All Services  
- Application Services  
- Technology Management Services  
- Service Offerings  

### 🌐 Network Path Scripts

These scripts visualize multi-hop infrastructure relationships:

- IP Router → IP Switch → Server  
- IP Switch → Server → Application  

### 🖥️ Server Inventory Scripts

These scripts break down server counts by platform:

- All Servers  
- ESX Servers  
- Linux Servers  
- Solaris Servers  
- Windows Servers  
- Azure VMs  

---

## 🛡️ Security & Privacy

All scripts have been **sanitized** to remove:

- Internal URLs or instance-specific links  
- Custom field names (`u_`, `ref_`, etc.) that may expose proprietary logic  
- Relationship type IDs unique to specific implementations  

> ⚠️ **Important:** Before deploying these scripts in production or sharing externally, ensure you:
> - Replace placeholder fields with your actual CMDB schema  
> - Use secure and approved icons or links  
> - Avoid exposing sensitive or proprietary data  

---

## 💡 Example Use Cases

- Operations Dashboards showing service coverage across infrastructure  
- Change Management Views to assess impact radius  
- Executive Summaries for service health and footprint  
- CMDB Quality Reports to highlight gaps or unmanaged components  
- Service Portfolio Dashboards to track offerings and classifications  
- Infrastructure Inventory Panels for platform-specific insights  
