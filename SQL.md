📅 𝗔𝗯𝗼𝘂𝘁 𝗗𝗮𝘁𝗮:

__**1. Menu Items Table**__
The menu_items dataset contains information about the items available on the menu. Each row represents a unique menu item, with the following columns:
• menu_item_id: Unique identifier for each menu item.
• item_name: The name of the menu item.
• category: The category or type of cuisine the item belongs to (e.g., American, Italian).
• price: The price of the menu item in dollars.

__**2. Order Details Table**__
The order_details dataset contains information about individual orders placed by customers. Each row represents a unique order detail, with the following columns:
• order_details_id: Unique identifier for each order detail record.
• order_id: Unique identifier for each order.
• order_date: The date when the order was placed, formatted as MM/DD/YY.
• order_time: The time when the order was placed.
• item_id: The identifier of the menu item ordered, corresponding to menu_item_id in the menu_items dataset.
