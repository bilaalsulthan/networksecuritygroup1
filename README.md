### Network Security Groups (NSGs) and Inspecting Network Protocols

#### Step 1: Create and Assign NSGs
- Navigate to the Azure portal and create a new **Network Security Group (NSG)**.
- Define inbound and outbound security rules based on your application requirements.
- Assign the NSG to the relevant subnet or network interface in your virtual network.

#### Step 2: Configure Security Rules
- Add security rules to allow or deny specific traffic:
  - Define rules for protocols like TCP, UDP, or ICMP.
  - Set priority levels to control rule precedence.
- Test the rules by attempting to connect to services and verifying expected behaviors.

#### Step 3: Inspect and Monitor Traffic
- Use Azure **Network Watcher** to analyze traffic patterns and diagnose issues.
- Enable **NSG flow logs** for deeper insights into traffic activity.
- Regularly review logs to identify and address potential security threats.
