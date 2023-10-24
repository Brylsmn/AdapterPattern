# Plugging Devices into Power Outlets
You are developing an application that helps users manage and control various electronic devices by plugging them into power outlets. Each device has different plug types, voltage, and amperage requirements. To ensure compatibility and safety, you need to create adapters for different devices to allow them to be plugged into standard power outlets.

  Adaptee Objects:

  Laptop - Represents a laptop device that needs to be plugged into a power source. It has the charge() method.

  Refrigerator - Represents a refrigerator device that requires a power source. It has the startCooling() method.

  SmartphoneCharger - Represents a smartphone charger that needs to be plugged in for charging. It has the chargePhone() method.

  Target Object:

  PowerOutlet - Represents a standard power outlet with a common interface for plugging in devices. It defines the plugIn() method as the target method.

  Adapter Objects:

  LaptopAdapter - An adapter for plugging a laptop into a standard power outlet. It adapts the Laptop to the PowerOutlet interface, translating plugIn() to charge().
  
  RefrigeratorAdapter - An adapter for plugging a refrigerator into a standard power outlet. It adapts the Refrigerator to the PowerOutlet interface, translating plugIn() to startCooling().
  
  SmartphoneAdapter - An adapter for plugging a smartphone charger into a standard power outlet. It adapts the SmartphoneCharger to the PowerOutlet interface, translating plugIn() to chargePhone().
# UML Class Diagram
![Alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/393622969_285759361088804_4773994227263647428_n.png?stp=dst-png_p403x403&_nc_cat=111&ccb=1-7&_nc_sid=510075&_nc_eui2=AeFALzAbZGiwxq0jI05qmRbAFMxhOxwgFtUUzGE7HCAW1XHNGD-Wyqonr7J4-WhyHIeSKDQVXDOkspQ_aLOuFZHy&_nc_ohc=MzPfqM_g6HsAX_0quYL&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdQSg_eey9JqIOzfTqCqOIZ7Xjc84VUKfIShKoOTCuea4g&oe=655585B1)
