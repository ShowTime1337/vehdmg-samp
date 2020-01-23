Vehicle damage system for SA-MP. (0.3.7)

	native GetVehicleParams(vehicleid, type);
	native SetVehicleParams(vehicleid, type, status, delay = 0);
	native GetVehicleBoot(vehicleid, &Float:x, &Float:y, &Float:z);
	native GetVehicleHood(vehicleid, &Float:x, &Float:y, &Float:z);
	native GetVehicleRoof(vehicleid, &Float:x, &Float:y, &Float:z);
	native GetVehicleRandomColors(modelid, &color1, &color2);
	native GetVehicleColor(vehicleid, &color1, &color2);
	native GetNearestVehicle(vehicleid);
	native GetVehiclePaintjob(vehicleid);
	native GetVehicleDriver(vehicleid);
	native GetVehicleTopSpeed(vehicleid);
	native GetVehicleInterior(vehicleid);
	native GetVehicleSeats(vehicleid);
	native GetVehicleModelSeats(modelid);
	native ResetVehiclePaintjob(vehicleid);
	native IsVehicleSeatOccupied(vehicleid, seatid);
	native IsValidVehicle(vehicleid);
