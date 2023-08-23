# **XR_Exporter**

## **Introduction**

**XR_Exporter** is a specialized internet exporter tailored for monitoring Cloud_XR connection statuses. While it's primarily based on the ping exporter and intended for Cloud_XR devices, its flexible design allows it to be used to check connections for other clients, provided you're aware of the port in use.

## **Features**

- **Cloud_XR Connection Monitoring:** By default, XR_Exporter monitors the connection status of Cloud_XR devices.
- **Flexible Port Checking:** Can be used to ping addresses of other clients by specifying the port number.

## **Getting Started**

### **Default Usage (Cloud_XR Connection)**

To monitor the Cloud_XR connection, simply run the provided executable:

```

./XR_Exporter.exe

```

### **Custom Usage (Other Connections)**

To use XR_Exporter for other connections, run the following command and replace **`portNumberHere`** with the appropriate port number:

```

go run xrcube.go -portToCheck=portNumberHere

```
