class SmartDevice {
    String brand;
    String model;
    double price;
    boolean wifiEnabled;

    SmartDevice() {
        this("Unknown", "Unknown", 0.0, false);
        System.out.println("Default Constructor called");
    }

    SmartDevice(String brand, String model) {
        this(brand, model, 0.0, false);
        System.out.println("Constructor with brand & model called");
    }

    SmartDevice(String brand, String model, double price) {
        this(brand, model, price, false);
        System.out.println("Constructor with brand, model & price called");
    }

    SmartDevice(String brand, String model, double price, boolean wifiEnabled) {
        this.brand = brand;
        this.model = model;
        this.price = price;
        this.wifiEnabled = wifiEnabled;
        System.out.println("Full Constructor called");
    }

    void displayInfo() {
        System.out.println("Brand: " + brand);
        System.out.println("Model: " + model);
        System.out.println("Price: ₹" + price);
        System.out.println("Wi-Fi Enabled: " + (wifiEnabled ? "Yes" : "No"));
        System.out.println("---------------------------------");
    }
}

public class SmartDeviceTest {
    public static void main(String[] args) {
        SmartDevice device1 = new SmartDevice();
        device1.displayInfo();

        SmartDevice device2 = new SmartDevice("Samsung", "Galaxy Watch 6");
        device2.displayInfo();

        SmartDevice device3 = new SmartDevice("Apple", "iPad Air", 59999.99);
        device3.displayInfo();

        SmartDevice device4 = new SmartDevice("Amazon", "Echo Dot", 4499.50, true);
        device4.displayInfo();
    }
}
