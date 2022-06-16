# Bypass TPM 2.0 check when installing Windows 11

Use the supplied registry.reg file to merge your registry settings or alternatively
you can follow the step by step guide bellow.

## Step 1
```Shift+F10```

## Step 2

```REG ADD HKLM\SYSTEM\Setup\LabConfig /v BypassTPMCheck /t REG_DWORD /d 1```

## Step 3

```REG ADD HKLM\SYSTEM\Setup\LabConfig /v BypassSecureBootCheck /t REG_DWORD /d 1```

## Step 4

```REG ADD HKLM\SYSTEM\Setup\LabConfig /v BypassRAMCheck /t REG_DWORD /d 1```