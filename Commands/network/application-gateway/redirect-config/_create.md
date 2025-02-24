# [Command] _network application-gateway redirect-config create_

Create a redirect configuration.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2FwcGxpY2F0aW9uZ2F0ZXdheXMve30=/2022-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/applicationgateways/{} 2022-05-01 properties.redirectConfigurations[] -->

#### examples

- Create a redirect configuration to a http-listener called MyBackendListener.
    ```bash
        network application-gateway redirect-config create -g MyResourceGroup --gateway-name MyAppGateway -n MyRedirectConfig --type Permanent --include-path true --include-query-string true --target-listener MyBackendListener
    ```

### [2023-02-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2FwcGxpY2F0aW9uZ2F0ZXdheXMve30=/2023-02-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/applicationgateways/{} 2023-02-01 properties.redirectConfigurations[] -->

#### examples

- Create a redirect configuration to a http-listener called MyBackendListener.
    ```bash
        network application-gateway redirect-config create -g MyResourceGroup --gateway-name MyAppGateway -n MyRedirectConfig --type Permanent --include-path true --include-query-string true --target-listener MyBackendListener
    ```

### [2023-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2FwcGxpY2F0aW9uZ2F0ZXdheXMve30=/2023-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/applicationgateways/{} 2023-06-01 properties.redirectConfigurations[] -->

#### examples

- Create a redirect configuration to a http-listener called MyBackendListener.
    ```bash
        network application-gateway redirect-config create -g MyResourceGroup --gateway-name MyAppGateway -n MyRedirectConfig --type Permanent --include-path true --include-query-string true --target-listener MyBackendListener
    ```
