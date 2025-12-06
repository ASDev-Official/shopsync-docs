# Location-Based Reminders

Get notified about your shopping lists when you're near a store.

!!! warning "Privacy First"
ShopSync only uses location when the app is open or when you've explicitly enabled reminders. Location data is never shared or sold.

## How It Works

1. Associate lists with store locations
2. Enable location reminders
3. Get notified when near the store
4. Open app and start shopping!

## Setting Up Reminders

### Associate List with Location

1. Open a shopping list
2. Tap **⋮** (more options)
3. Select **Set Location**
4. Search for store or drop pin
5. Set reminder radius (50m - 500m)
6. Save

### Enable Notifications

Make sure notifications are enabled:

1. Go to **Settings** → **Notifications**
2. Enable **Location Reminders**
3. Choose notification style
4. Set quiet hours (optional)

## Managing Locations

### Saved Locations

Store frequently visited locations:

1. Go to **Settings** → **Locations**
2. Tap **Add Location**
3. Name it (e.g., "Costco Downtown")
4. Search or drop pin
5. Save for quick assignment

### Edit Location

1. Open list
2. Tap location name
3. Adjust pin or radius
4. Save changes

### Remove Location

1. Open list
2. Tap location name
3. Select **Remove Location**
4. Confirm

## Notification Settings

### Customize Notifications

**Trigger Distance:**

- Close (50m)
- Nearby (100m)
- Medium (250m)
- Far (500m)

**Notification Style:**

- Silent notification
- Sound + vibration
- Alert only when unlocked

**Frequency:**

- Once per visit
- Every entry
- Daily maximum

### Quiet Hours

Disable reminders during specific times:

1. Go to **Settings** → **Location Reminders**
2. Enable **Quiet Hours**
3. Set start and end time
4. Choose days of week

## Privacy & Permissions

### Required Permissions

=== "Android" - **Location (When in Use)**: Required - **Background Location**: Optional (for better accuracy) - **Notifications**: Required

=== "iOS" - **Location (When in Use)**: Required - **Location (Always)**: Optional (for background reminders) - **Notifications**: Required

### Location Data

ShopSync location data:

✅ **Stored locally on device**  
✅ **Optional sync to Firebase (encrypted)**  
✅ **Used only for reminders**  
✅ **Can be deleted anytime**

❌ **Never shared with third parties**  
❌ **Not used for advertising**  
❌ **Not sold or monetized**

## Best Practices

### Accuracy Tips

- Set radius 100-250m for best results
- Use specific store locations
- Enable background location
- Keep location services on

### Battery Optimization

- Use larger radius (less frequent checks)
- Limit number of active reminders
- Disable when traveling
- Use "When in Use" permission only

### Effective Reminders

- Link lists to specific stores
- Use saved locations for frequent shops
- Set reasonable trigger distances
- Review and clean up old reminders

## Troubleshooting

### Not Getting Reminders

1. Check location permissions
2. Verify notifications enabled
3. Ensure location services on
4. Check battery optimization settings
5. Increase reminder radius

### Too Many Notifications

- Increase trigger distance
- Enable quiet hours
- Set "Once per visit" frequency
- Remove unnecessary locations

### Inaccurate Triggers

- Recalibrate device location
- Increase reminder radius
- Use Wi-Fi for better accuracy
- Update store location pin

!!! tip "Multiple Stores"
Have multiple nearby grocery stores? Create separate lists or set wider radius to catch multiple locations.

## Examples

### Grocery Store

```
List: Weekly Groceries
Location: Whole Foods Market
Radius: 200m
Notification: Sound + Vibration
```

### Hardware Store

```
List: Home Improvement
Location: Home Depot
Radius: 300m
Notification: Silent
Quiet Hours: 9 PM - 8 AM
```

### Pharmacy

```
List: Prescriptions
Location: CVS Pharmacy
Radius: 150m
Notification: Alert when unlocked
```

---

See also: [Settings](../user-guide/settings.md) | [Managing Lists](../user-guide/managing-lists.md)
