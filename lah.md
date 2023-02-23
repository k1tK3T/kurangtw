Sleep(int ms)

Sleep for the given number of milliseconds.

LogToConsole(string text)

Display the given text on the Growtopia console.

SendPacket(int type, string text)

Send a text packet to the server.

SendPacketRaw(TankPacket packet, bool client [, int flags])

Send a TankPacket to the server/client. The default value of flags is 1.

SendVariantList(VariantList varlist [, int netid][, int delay])

Call the VariantList. The default value of netid is -1, and delay is 0.

RequestJoinWorld(string world_name)

Wrapper for join world (sending action|join_request).

FindPath(int x, int y [, int delay])

Find the path. The default value of delay is 20.

GetCamera()

Return the world camera.

GetClient()

Return the ENet client.

GetInventory()

Return the inventory items. The key is item id.

GetItemInfo(int id)

Return the item info for the given id.

GetItemInfo(string item_name)

Return the item info for the given name.

GetItemInfoList()

Return the list of item info. The key is item id.

GetLocal()

Return the local NetAvatar.

GetNPC(int npc_id)

Return the ClientNPC for the given id.

GetNPCList()

Return the list of ClientNPC. The key is npc id.

GetObjectList()

Return the list of WorldObject. The key is object id.

GetPlayer(int netid)

Return the NetAvatar for the given netid.

GetPlayerList()

Return the list of NetAvatar. The key is player netid.

GetPlayerInfo()

Return the PlayerInfo.

GetTile(int tile_x, int tile_y)

Return the Tile for the given tile coordinates.

GetTiles()

Return the list of Tile. The key is tile index (0 - tilecount).

GetWorld()

Return the World.

Hash32(string text [, uint32 seed])

Proton hashing returning 32byte int.

Hash64(string text [, uint64 seed])

Proton hashing returning 64byte int.

ChangeValue(string id, bool state)

Change the internal menu state.

ChangeValue(string id, int value)

Change the internal variable value.

GetAsyncKeyState(int key)

Return the asynchronous key state for the given key.

GetAsyncKeyState(char key)

Return the asynchronous key state for the given key.

AttachConsole()

Enable the standard console.

DetachConsole()

Destroy the standard console.

Encrypt(string text [, int key])

Encrypt the given text. The default value of key is 0.

LoadEncrypt(string text [, int key])

Load the encrypted text. The default value of key is 0.

EncryptFile(string file_name [, int key])

Encrypt the existing file from the script list. The output will be file_name + “_enc”. The default value of key is 0.

LoadEncryptedFile(string file_name [, int key])

Load the existing encrypted file. The default value of key is 0.
