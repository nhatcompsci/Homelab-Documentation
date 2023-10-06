
# About

My homelab's centerpiece is a custom-built bare-metal server turned into a native hypervisor. It handles virtual machines and various projects with ease, thanks to its carefully selected hardware.



## B-rolls

![App Screenshot](https://nhatblog.com/wp-content/uploads/2023/01/DSC00372-768x577.jpg)

![App Screenshot](https://nhatblog.com/wp-content/uploads/2023/01/DSC00379-768x577.jpg)

## Documentation

**CPU**: [Intel Xeon E5 2640v4 2.40 GHz with 10 cores 20 threads](https://www.intel.com/content/www/us/en/products/sku/92984/intel-xeon-processor-e52640-v4-25m-cache-2-40-ghz/specifications.html)

**Motherboard**: [MACHINIST X99 LGA 2011-V3 ATX](https://www.amazon.com/MACHINIST-Motherboard-Support-Channel-X99-RS9/dp/B09X1JGMXN?th=1)

**RAM**: [Samsung 16Gb DDR4-2133P ECC Registered Memory](https://www.amazon.com/Samsung-Pc4-17000P-Ddr4-2133P-Registered-Memory/dp/B00UBHSH0W) x4

**GPU**: [Gigavino GT730](https://www.amazon.com/Gigavino-GT730-GeforceHDMI-Tarjeta-510054/dp/B0B5ZNN2CQ)

**Storages**: 

* [Micron 256GB M.2]()

* [Sandisk 1TB SSD](https://www.amazon.com/gp/product/B01F9G43WU/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)

* [Western Digital 4TB WD Red NAS HDD](https://www.westerndigital.com/products/internal-drives/wd-red-sata-hdd?sku=WD20EFAX) x2



**Case**: [ZEUS GAMDIAS](https://www.gamdias.com/en/component/case/TALOS_E3_WH)

**Cooling**: [ID-COOLING SE-214-XT](https://www.idcooling.com/Product/detail/id/276/name/SE-214-XT%20ARGB)

**PSU**: [ARESGAME 550W](https://www.amazon.com/ARESGAME-Supply-80Plus-Bronze-Non-Modular/dp/B09Y826BQ4?th=1)


## Description

To ensure optimal virtual machine creation and management, I selected the __Intel Xeon E5 2640v4__, running at 2.40 GHz, boasting 10 cores and 20 threads, as the brains of this server. This choice was influenced by its compatibility with the LGA 2011-V3 bracket. 

After some searching, I found the __MACHINIST X99__ LGA 2011-V3 ATX motherboard, which perfectly matched my CPU requirements. It not only supports the CPU but also offers four DDR4 RAM slots, a superior choice due to its speed compared to DDR3 or DDR2.

In terms of memory, I settled on 64GB of ECC RAM, which should suffice for the hypervisor's needs. Additionally, as I plan to build a virtual-based NAS, ECC memory is crucial for data integrity. ECC, or Error Correction Code, memory can automatically detect and correct memory errors, which is vital for NAS data.

For ECC RAM, I found the __Samsung 16GB DDR4-2133P ECC__ Registered Memory, which strikes a good balance between cost and effectiveness.

Now, moving on to other essential components:

GPU: I opted for the __Gigavino GT730__, as the Xeon CPU lacks an integrated GPU. This graphics card is necessary for the initial server setup and visual output.

PSU: The __ARESGAME 550W__ PSU should provide ample power for this server while remaining energy-efficient.

Disks: I've chosen a __Micron 256GB M.2__ SSD for the Proxmox hypervisor OS, a __1TB Sandisk__ SSD for Virtual Machines, and two __Western Digital 4TB__ WD Red NAS HDDs for a future NAS setup.

Case: The __ZEUS GAMDIAS__ ATX case adds a touch of style to this compact setup.

Cooling: To maintain optimal CPU temperatures, I've included the __ID-COOLING SE-214-XT__ cooling solution.

