# [Command] _mobile-network sim delete_

Delete the specified SIM.

## Versions

### [2022-11-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5tb2JpbGVuZXR3b3JrL3NpbWdyb3Vwcy97fS9zaW1zL3t9/2022-11-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.mobilenetwork/simgroups/{}/sims/{} 2022-11-01 -->

#### examples

- Delete sim
    ```bash
        mobile-network sim delete -g rg -n sim-name --sim-group-name sim-group-name -y
    ```
