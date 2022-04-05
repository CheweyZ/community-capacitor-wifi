## API

<docgen-index>

* [`scan()`](#scan)
* [`getIP()`](#getip)
* [`getSSID()`](#getssid)
* [`connect(...)`](#connect)
* [`connectPrefix(...)`](#connectprefix)
* [`disconnect()`](#disconnect)
* [Interfaces](#interfaces)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### scan()

```typescript
scan() => Promise<{ scan: IWifiNetwork[]; }>
```

**Returns:** <code>Promise&lt;{ scan: IWifiNetwork[]; }&gt;</code>

--------------------


### getIP()

```typescript
getIP() => Promise<{ ip: string | null; }>
```

**Returns:** <code>Promise&lt;{ ip: string | null; }&gt;</code>

--------------------


### getSSID()

```typescript
getSSID() => Promise<{ ssid: string | null; }>
```

**Returns:** <code>Promise&lt;{ ssid: string | null; }&gt;</code>

--------------------


### connect(...)

```typescript
connect(options: { ssid: string; password?: string; joinOnce?: boolean; isHiddenSsid?: boolean; }) => Promise<{ ssid: string | null; }>
```

| Param         | Type                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------- |
| **`options`** | <code>{ ssid: string; password?: string; joinOnce?: boolean; isHiddenSsid?: boolean; }</code> |

**Returns:** <code>Promise&lt;{ ssid: string | null; }&gt;</code>

--------------------


### connectPrefix(...)

```typescript
connectPrefix(options: { ssid: string; password?: string; joinOnce?: boolean; }) => Promise<{ ssid: string | null; }>
```

| Param         | Type                                                                  |
| ------------- | --------------------------------------------------------------------- |
| **`options`** | <code>{ ssid: string; password?: string; joinOnce?: boolean; }</code> |

**Returns:** <code>Promise&lt;{ ssid: string | null; }&gt;</code>

--------------------


### disconnect()

```typescript
disconnect() => Promise<void>
```

--------------------


### Interfaces


#### IWifiNetwork

| Prop               | Type                |
| ------------------ | ------------------- |
| **`level`**        | <code>number</code> |
| **`SSID`**         | <code>string</code> |
| **`BSSID`**        | <code>string</code> |
| **`frequency`**    | <code>number</code> |
| **`capabilities`** | <code>string</code> |
| **`timestamp`**    | <code>number</code> |
| **`channelWidth`** | <code>number</code> |
| **`centerFreq0`**  | <code>number</code> |
| **`centerFreq1`**  | <code>number</code> |

</docgen-api>