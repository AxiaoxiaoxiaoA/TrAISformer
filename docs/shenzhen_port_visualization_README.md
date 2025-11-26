# 深圳港口区域与航线可视化 (Shenzhen Port Visualization)

This is an interactive web visualization of Shenzhen Port areas and shipping routes based on the official "深圳港口章程" (Shenzhen Port Regulations) published by Shenzhen Transportation Bureau on July 7, 2023.

## Features

- **Three Port Areas**: West Port (西部港区), East Port (东部港区), and Xiaomo Port (小漠港区)
- **Water Boundaries**: Visualized water domain boundaries with control point markers
- **Land Ports**: Major dock areas including Nanshan, Dachanwan, Baoan, Yantian, and Dapeng
- **Shipping Channels**: Main and secondary navigation routes
- **Anchorage Areas**: 13 designated anchorage zones with anchor markers
- **Interactive Controls**: Toggle layers on/off, zoom controls, hover tooltips

## How to Use

1. Open `shenzhen_port_map.html` in any modern web browser
2. Use the layer controls on the right panel to show/hide different map layers
3. Hover over port areas, channels, or anchorages to see detailed information
4. Click on areas to display information in the info panel
5. Use zoom buttons (+/-) or scroll to zoom the map

## Port Areas Covered

### West Port (西部港区)
- Nanshan Port Area (南山港区)
- Dachanwan Port Area (大铲湾港区)  
- Baoan Port Area (宝安港区)

### East Port (东部港区)
- Yantian Port Area (盐田港区)
- Dapeng Port Area (大鹏港区)

### Xiaomo Port (小漠港区)
- Located in Shenshan Special Cooperation Zone (深汕特别合作区)

## Major Shipping Channels

| Channel Name | Capacity | Notes |
|-------------|----------|-------|
| 铜鼓航道 | 20万吨级 (200,000 DWT) | Main west channel |
| 大鹏湾航道 | 20万吨级 (200,000 DWT) | Natural east channel |
| 盐田港区航道 | 20万吨级 (200,000 DWT) | Container ships |
| 三门水道 | 10万吨级 (100,000 DWT) | Natural channel |

## Coordinate Reference

The visualization covers the following geographic area:
- Longitude: 113.5°E - 115.2°E
- Latitude: 22.1°N - 22.8°N

## Technical Notes

- Built with pure HTML/CSS/SVG - no external dependencies required
- Works offline without internet connection
- Compatible with all modern browsers
- Responsive design for different screen sizes

## Data Source

All port boundary coordinates, channel specifications, and anchorage information are based on the official "深圳港口章程" document published by the Shenzhen Transportation Bureau (深圳市交通运输局).

## Screenshot

![Shenzhen Port Visualization](https://github.com/user-attachments/assets/b2636988-d082-40f8-81fc-ada2c3a0c593)
