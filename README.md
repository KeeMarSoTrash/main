local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v62,v63)local v83={};for v122=1925 -(1034 + 890), #v62 do v6(v83,v0(v4(v1(v2(v62,v122,v122 + 1)),v1(v2(v63,1 + 0 + ((v122-(1 + 0))% #v63),(1761 -(1045 + 715)) + ((v122-(2 -(1 -0)))% #v63) + 1 + 0 + 0 + 0)))%(2218 -(1230 + 732))));end return v5(v83);end local v8={[v7("\114\140\126\200\74\146\94\205\72\128","\37\229\16\172")]=v7("\212\241\235\5\182\178\233\215\225\236","\159\148\142\72\215\192\201"),[v7("\247\233\139\93\198","\180\134\231\50")]=Color3.fromRGB((758 -217) -(49 + 237),0,0),[v7("\218\77\173\0\131\255\76","\145\40\212\98\234")]=Enum.KeyCode.RightControl};local v9=loadstring(game:HttpGet(v7("\124\91\209\189\103\21\138\226\102\78\210\227\115\70\209\165\97\77\208\190\113\93\198\162\122\91\192\163\96\1\198\162\121\0\228\161\113\87\247\254\38\0\231\191\117\76\206\168\96\0\200\172\125\65\138\143\102\78\198\166\113\91\243\254\58\67\208\172","\20\47\165\205")))();local v10=v9:CreateWindow(v8,game:GetService(v7("\158\181\38\137\121\184\13","\221\218\84\236\62\205\100\174")));local v11=v10:CreateTab(v7("\141\208\158\47\112\168\143\235\234\132\42\108\170\137\191\214\159","\203\185\237\71\25\198\232"));local v12=v10:CreateTab(v7("\154\123\254\38","\215\18\141\69"));local v13=v11:CreateSection("");local v14=v11:CreateSection("");local v15=v12:CreateSection("");local v16=game:GetService(v7("\193\57\119\21\201\94\229\37\122\35","\147\76\25\70\172\44"));local v17=game.Players.LocalPlayer;local v18=v17.Character.HumanoidRootPart;local v19=v17:GetMouse();local v20=game:GetService(v7("\189\21\190\134\153\31\160\151\186\21\160\149\128\19\183","\233\112\210\227"));local v21=game:service(v7("\146\215\19\190\203\14\95\79\183\219\19","\196\190\97\202\190\111\51\26"));local v22=game:GetService(v7("\19\210\101\230\40\212\116\254\36\211\70\254\46\197\116\237\36","\65\183\21\138")).ToolsCache[v17.UserId];local v23;local v24;local v25;local v26;local v27;local v28;local v29;local v30=game.PlaceId;local v31={};local v32="";local v33=os.date(v7("\99\85\45","\66\127\89\25\181\116\28")).hour;local v34=false;local v35=pcall(function()v31=game:GetService(v7("\170\183\18\170\11\135\177\16\179\59\135","\226\195\102\218\88")):JSONDecode(readfile(v7("\162\56\232\236\141\58\249\236\137\37\234\218\158\36\178\213\159\56\242","\236\87\156\191")));end);if  not v35 then local v84=0;local v85;local v86;while true do if (v84==1) then while true do if (v85==0) then v86=0 + 0;while true do if (v86==0) then table.insert(v31,v33);writefile(v7("\11\18\243\65\54\112\32\46\226\96\33\120\55\14\169\120\36\114\43","\69\125\135\18\87\29"),game:GetService(v7("\139\89\225\223\32\21\1\181\68\246\202","\195\45\149\175\115\112\115")):JSONEncode(v31));break;end end break;end end break;end if (v84==0) then v85=(842 + 458) -(1249 + 51);v86=nil;v84=1;end end end TPReturner=function()local v87=0;local v88;local v89;local v90;local v91;while true do if (v87==0) then v88=0 + 0 + 0;v89=nil;v87=1;end if (v87==1) then v90=nil;v91=nil;v87=2;end if (v87==2) then while true do if (v88==(1 + 0)) then local v139=(8208 -6210) -((2329 -(311 + 177)) + (399 -242));while true do if ((0 -(0 -0))==v139) then v90="";if (v89.nextPageCursor and (v89.nextPageCursor~=v7("\210\111\32\78","\188\26\76\34\164\128\80")) and (v89.nextPageCursor~=nil)) then v32=v89.nextPageCursor;end v139=1 -0;end if (v139==(1 + 0)) then v88=2 + 0;break;end end end if (v88==0) then local v140=0;local v141;while true do if (v140==0) then v141=194 -(41 + 153);while true do if (0==v141) then local v177=0;while true do if (v177==1) then v141=1;break;end if (0==v177) then v89=nil;if (v32=="") then v89=game.HttpService:JSONDecode(game:HttpGet(v7("\181\186\15\48\174\244\84\111\186\175\22\37\174\224\9\47\191\162\20\56\243\173\20\45\242\184\74\111\186\175\22\37\174\225","\221\206\123\64")   .. v30   .. v7("\241\241\234\208\41\33\88\173\173\223\215\61\40\67\189\189\252\205\45\48\101\172\230\234\208\98\5\89\189\164\227\203\50\45\94\227\179\191\146","\222\130\143\162\95\68\42")));else v89=game.HttpService:JSONDecode(game:HttpGet(v7("\232\36\232\221\17\186\127\179\202\3\237\53\239\131\16\239\50\240\194\26\174\51\243\192\77\246\97\179\202\3\237\53\239\130","\128\80\156\173\98")   .. v30   .. v7("\171\226\133\56\173\225\227\147\101\139\241\243\140\35\184\187\226\143\56\175\203\227\132\47\169\185\208\147\41\253\232\248\141\35\175\185\160\208\122\253\231\228\146\57\180\246\172","\132\145\224\74\219")   .. v32));end v177=1;end end end if (v141==(1 + 0)) then v88=1;break;end end break;end end end if (v88==(2 -0)) then v91=(1535 -906) -(269 + (2354 -(1207 + 787)));for v144,v145 in pairs(v89.data) do local v146=(0 -0) -(507 -(259 + 248));local v147;local v148;while true do if (v146==(1 + 0)) then while true do if (v147==1) then if (tonumber(v145.maxPlayers)>tonumber(v145.playing)) then local v188=0;while true do if (v188==((478 -124) -((657 -(161 + 173)) + (1125 -(486 + 608))))) then for v199,v200 in pairs(v31) do local v201=0;while true do if (v201==(0 -0)) then if (v91~=(0 -(1411 -(1205 + 206)))) then if (v90==tostring(v200)) then v148=false;end elseif (tonumber(v33)~=tonumber(v200)) then local v217=pcall(function()local v220=0;local v221;local v222;while true do if (v220==1) then while true do if (v221==(806 -((1209 -411) + 4 + 4))) then v222=0 -0;while true do if (v222==(0 + 0)) then delfile(v7("\130\182\229\245\248\161\188\194\195\235\186\188\227\213\183\166\170\254\200","\204\217\145\166\153"));v31={};v222=1737 -(1590 + 146);end if (v222==(1 + 0)) then table.insert(v31,v33);break;end end break;end end break;end if (v220==0) then v221=0;v222=nil;v220=1;end end end);end v91=v91 + (1 -0) + (0 -0);break;end end end if (v148==true) then local v210=867 -(439 + 428);local v211;while true do if (v210==(0 + 0)) then v211=0;while true do if (v211==(177 -(15 + 162))) then local v218=0;local v219;while true do if (v218==0) then v219=949 -(658 + (1684 -(322 + 1071)));while true do if (v219==(929 -(916 + 12))) then v211=3 -(278 -(86 + 190));break;end if (v219==(0 + (0 -0))) then table.insert(v31,v90);wait();v219=1 + 0;end end break;end end end if (v211==(2 -1)) then pcall(function()local v223=(1991 -(1467 + 524)) + 0;local v224;while true do if (v223==0) then v224=0;while true do if (((895 -(455 + 440)) -0)==v224) then local v225=1054 -(607 + 447);while true do if (v225==(0 -0)) then writefile(v7("\122\174\41\157\162\253\81\146\56\188\181\245\70\178\115\164\176\255\90","\52\193\93\206\195\144"),game:GetService(v7("\240\245\30\61\101\135\229\206\232\9\40","\184\129\106\77\54\226\151")):JSONEncode(v31));wait();v225=1 + 0;end if (v225==1) then v224=1 -(0 -0);break;end end end if (v224==(812 -(301 + 510))) then game:GetService(v7("\239\160\28\129\57\182\170\159\232\160\2\146\32\186\189","\187\197\112\228\73\217\216\235")):TeleportToPlaceInstance(v30,v90,game.Players.LocalPlayer);break;end end break;end end end);wait(1936 -(1423 + 509));break;end end break;end end end break;end end end break;end if (v147==(559 -(84 + 475))) then local v181=0;while true do if (v181==1) then v147=(8 -5) -2;break;end if (v181==(0 + 0 + 0)) then v148=true;v90=tostring(v145.id);v181=2 -1;end end end end break;end if (v146==0) then v147=0 + 0;v148=nil;v146=1;end end end break;end end break;end end end;switchServer=function()while wait() do pcall(function()local v132=92 -(42 + 50);local v133;while true do if (v132==0) then v133=0;while true do if (v133==(0 -0)) then TPReturner();if (v32~="") then TPReturner();end break;end end break;end end end);end end;teleport=function(v64)local v92=(0 -0) + 0;while true do if (v92==((2 -1) + (0 -0))) then wait();game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=v64;break;end if (v92==0) then local v135=(0 -0) + (0 -0);while true do if (v135==1) then v92=1 + 0;break;end if (0==v135) then v24=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame;if game.Players.LocalPlayer.Character.Humanoid.Sit then game.Players.LocalPlayer.Character.Humanoid.Sit=false;end v135=2 -1;end end end end end;for v65,v66 in pairs(v17.Character:GetChildren()) do if (v66:IsA(v7("\77\48\27\28","\25\95\116\112\114")) and v66:FindFirstChild(v7("\51\6\61\201\213\252","\116\116\84\185\150\205\110"))) then v23=v66.Name;end end EquipTool=function()local v93=0 -0;local v94;while true do if (v93==(601 -(161 + 440))) then local v136=0;while true do if (v136==(0 -0)) then game:GetService(v7("\248\45\59\134\20\56\61\100\207\44\24\158\18\41\61\119\207","\170\72\75\234\125\91\92\16")).CloudFrameShared.DataStreams.SetEquippedItem:InvokeServer(2);v94={[(834 -(425 + 17)) -((43 -27) + 375)]=game:GetService(v7("\125\195\232\123\73\68\218\91\195\252\68\84\72\201\78\193\253","\47\166\152\23\32\39\187")).ToolsCache:FindFirstChild(v17.UserId)[v23]};v136=1 + 0;end if (v136==(1 + 0)) then v93=1 + 0;break;end end end if (v93==(1221 -(1127 + 93))) then game:GetService(v7("\191\65\212\244\24\229\214\153\65\192\203\5\233\197\140\67\193","\237\36\164\152\113\134\183")).CloudFrameShared.DataStreams.EquipTool:FireServer(unpack(v94));break;end end end;game:service(v7("\50\215\11\36\32\159\17","\98\187\106\93\69\237")).LocalPlayer.Idled:connect(function()local v95=0;local v96;while true do if (v95==0) then v96=0;while true do if (v96==0) then v21:CaptureController();v21:ClickButton2(Vector2.new());break;end end break;end end end);v13:CreateLabel(v7("\193\70\231\33\160\13\250","\135\39\149\76\201\99\157"));v15:CreateLabel(v7("\175\71\191\251","\226\46\204\152\24"));local v36=v13:CreateToggle(v7("\36\149\186\185\140\2\133\9\140","\101\224\206\214\172\73\236"),nil,function(v67)local v97=1238 -(121 + 616 + (1552 -1051));local v98;while true do if ((0 + 0)==v97) then v98=(706 + 618) -(391 + 933);while true do if (v98==((6873 -5468) -((1132 -742) + 626 + 389))) then shared.toggle=v67;if shared.toggle then v25=v16.Stepped:Connect(function()for v174,v175 in pairs(game.Workspace:GetChildren()) do if (v175:FindFirstChild(v7("\122\77\133\141\70\64","\50\40\228\225")) and v175:FindFirstChild(v7("\44\27\77\125\74\196\194\218\22\28\123\106","\101\104\30\24\43\137\173\180"))) then if game.Players.LocalPlayer.Character:FindFirstChildOfClass(v7("\11\161\222\254","\95\206\177\146\26\193")) then for v191,v192 in pairs(v17.Character:GetChildren()) do if (v192:IsA(v7("\26\165\1\163","\78\202\110\207\58")) and v192:FindFirstChild(v7("\195\107\116\89\199\40","\132\25\29\41"))) then v23=v192.Name;end end teleport(v175.HumanoidRootPart.CFrame + Vector3.new(0 -0,16 + 14,0 + 0));wait(1 + 0);game:GetService(v7("\36\32\144\26\254\21\36\148\19\243\37\49\143\4\246\17\32","\118\69\224\118\151")).CloudFrameShared.DataStreams.MonsterHit:FireServer(workspace[v175.Name],tostring(v23),true);break;elseif  not game.Players.LocalPlayer.Character:FindFirstChildOfClass(v7("\145\226\56\35","\197\141\87\79\217\209")) then EquipTool();break;end end end end);else local v160=1375 -(533 + 842);local v161;while true do if (v160==(1531 -(242 + 1289))) then v161=998 -(161 + 837);while true do if (v161==((0 -0) -0)) then v25:Disconnect();teleport();break;end end break;end end end break;end end break;end end end);local v37=v13:CreateToggle(v7("\53\178\100\138\168\63\174\124\137\168\57\168\114\135\241\84\144\127\138\236","\116\199\16\229\136"),nil,function(v68)local v99=0;local v100;local v101;while true do if (v99==0) then v100=(70 + 39) -(84 + 25);v101=nil;v99=1;end if (v99==1) then while true do if (v100==0) then v101=0;while true do if (v101==(372 -((472 -236) + (1103 -(916 + 51))))) then shared.toggle=v68;if shared.toggle then v26=v16.Stepped:Connect(function()for v184,v185 in pairs(game.Workspace:GetChildren()) do if (v185:FindFirstChild(v7("\194\198\10\4\248\52","\138\163\107\104\140\92")) and v185:FindFirstChild(v7("\13\209\138\218\37\239\182\209\55\214\188\205","\68\162\217\191")) and (v185.Name==v7("\208\87\94\162\231\5\242\92","\157\56\60\219\176\106"))) then if game.Players.LocalPlayer.Character:FindFirstChildOfClass(v7("\203\120\37\206","\159\23\74\162\211\163\36\181")) then for v202,v203 in pairs(v17.Character:GetChildren()) do if (v203:IsA(v7("\57\40\244\242","\109\71\155\158\60\193\67")) and v203:FindFirstChild(v7("\36\205\127\54\32\142","\99\191\22\70"))) then v23=v203.Name;end end teleport(v185.HumanoidRootPart.CFrame + Vector3.new(165 -(145 + 20),1750 -(1063 + 637),0));wait(1 + 0 + 0 + 0);game:GetService(v7("\135\85\195\25\188\83\210\1\176\84\224\1\186\66\210\18\176","\213\48\179\117")).CloudFrameShared.DataStreams.MonsterHit:FireServer(workspace[v185.Name],tostring(v23),true);break;elseif  not game.Players.LocalPlayer.Character:FindFirstChildOfClass(v7("\3\141\215\191","\87\226\184\211\157\167")) then EquipTool();break;end end end end);else local v176=0 -0;while true do if (v176==0) then v26:Disconnect();teleport();break;end end end break;end end break;end end break;end end end);local v38=v13:CreateToggle(v7("\211\53\196\20\244\254\234\80\224\55","\129\80\160\97\151\155\202\28"),nil,function(v69)local v102=0;local v103;while true do if (v102==(0 -(0 + 0))) then v103=0 -0;while true do if (v103==(0 + 0)) then toggle=v69;if toggle then while toggle do local v165=0;while true do if ((0 + 0 + 0)==v165) then wait(2 + 28);for v182,v183 in pairs(game.Workspace.DroppedItems:GetChildren()) do if v183:IsA(v7("\48\114\170\128\18","\125\29\206\229\126\104\121\167")) then v183:Destroy();end end break;end end end end break;end end break;end end end);local v39=v13:CreateToggle(v7("\51\242\188\32\82\203\167\44\25\167\132\42\21\226\166\43\19\245\177\111\59\243\173\34\1","\114\135\200\79"),nil,function(v70)local v104=0;local v105;while true do if (v104==(0 -(0 + 0))) then v105=575 -(307 + 268);while true do if ((0 + 0)==v105) then toggle=v70;if toggle then while toggle do local v166=0;local v167;while true do if (v166==((1611 -(747 + 864)) -(1814 -(1603 + 211)))) then v167=0 + 0 + 0;while true do if (v167==((0 + 0) -0)) then wait(1768.1 -(918 + 850));for v193,v194 in pairs(game.Players.LocalPlayer.PlayerGui.Interface.Inventory.Inventory.Frame.Backpack.List.Container:GetChildren()) do if string.match(v194.Name,v7("\160\7\57","\203\98\64\83\235\67")) then for v204,v205 in pairs(v194:GetDescendants()) do if v205:IsA(v7("\31\74\67\20","\75\37\44\120\107\100\157\28")) then if (v205.RarityLevel.Value>=5) then if (v194.DraggableComponent.Contents.LockIcon.Visible==false) then local v213=286 -(183 + 103);local v214;local v215;while true do if (v213==1) then while true do if (((737 -(274 + 463)) + 0 + 0)==v214) then print(v194.Name,v205.Name,v205.RarityLevel.Value);v215={[1]=v7("\102\210\188\174\99","\50\189\211\194\16\201"),[2]=v194.Name,[3]=true};v214=3 -2;end if (v214==((429 -163) -((1200 -(19 + 1166)) + 250))) then game:GetService(v7("\134\127\10\39\49\134\181\110\31\47\11\145\187\104\27\44\61","\212\26\122\75\88\229")).CloudFrameShared.DataStreams.SetInventoryItemLock:InvokeServer(unpack(v215));break;end end break;end if (v213==(911 -(451 + 31 + 429))) then v214=0;v215=nil;v213=1;end end end end end end end end break;end end break;end end end end break;end end break;end end end);v39:AddToolTip(v7("\57\165\187\212\147\255\159\39\171\170\214\130\226\133\75\152\167\241\130\225\218\5\160\168\207\158\166\227\5\129\191\216\137\242\159\55\170\154\216\132\244\218\31","\107\196\201\189\231\134\191"));local v40=v13:CreateToggle(v7("\253\174\100\52\148\54\221\174\119\51\192","\188\219\16\91\180\117"),nil,function(v71)local v106=0 -(751 -(328 + 423));local v107;while true do if (v106==(0 -(308 -(55 + 253)))) then v107=633 -(512 + 98 + 23);while true do if (v107==(0 -0)) then toggle=v71;while toggle do local v149=0 + 0;local v150;while true do if (v149==(0 -(738 -(324 + 414)))) then v150=0 -0;while true do if (0==v150) then wait((3378.6 -2240) -(857 + 279));game:GetService(v7("\55\77\237\201\69\205\4\92\248\193\127\218\10\90\252\194\73","\101\40\157\165\44\174")).CloudFrameShared.DataStreams.FishCaught:FireServer();break;end end break;end end end break;end end break;end end end);local v41=v13:CreateToggle(v7("\25\32\27\195\167\42\249\88\52","\88\85\111\172\135\121\156\52"),nil,function(v72)local v108=1247 -((2719 -1665) + 193);local v109;while true do if (v108==(1986 -(363 + 1356 + (1022 -755)))) then v109=0 + 0;while true do if (v109==(0 + 0)) then toggle=v72;while toggle do local v151=0;local v152;while true do if (v151==(0 -(0 -0))) then v152=0;while true do if (v152==0) then wait(2.6);game:GetService(v7("\30\112\100\93\16\67\45\97\113\85\42\84\35\103\117\86\28","\76\21\20\49\121\32")).CloudFrameShared.DataStreams.processGameItemSold:InvokeServer(v7("\244\127\23\51\226\108\30\45\222\110\19\54\201\125","\167\26\123\95"));break;end end break;end end end break;end end break;end end end);local v42=v13:CreateToggle(v7("\115\176\43\241\161\253\124\103\186\33","\33\213\70\158\215\152\92"),nil,function(v73)local v110=0;while true do if ((563 -(165 + (1176 -778)))==v110) then toggle=v73;while toggle do local v138=(2430 -(363 + 622)) -((3008 -(719 + 1132)) + (962 -674));while true do if (v138==3) then local v153=0;while true do if (1==v153) then v138=4;break;end if (v153==((219 -55) -((125 -46) + 44 + 41))) then game.Lighting.Bloom:Destroy();game.Lighting.Blur:Destroy();v153=1 + 0;end end end if (((1 + 1) -0)==v138) then local v154=0;while true do if (v154==((266 + 446) -((74 -22) + 659))) then v138=(7 -4) + (1314 -(21 + 1293));break;end if ((1343 -(937 + 406))==v154) then game.Lighting.Lighting:Destroy();game.Lighting.ColorCorrection:Destroy();v154=1;end end end if (v138==((467 -(161 + 305)) + 0)) then local v155=0;while true do if (v155==(1 + 0)) then v138=934 -(920 + 12);break;end if (v155==0) then game.Lighting.GlobalLighting:Destroy();game.Lighting.Atmosphere:Destroy();v155=1;end end end if (v138==0) then local v156=0 -(0 + 0);while true do if (v156==0) then if (game.Lighting.FogEnd==100) then game.Lighting.FogEnd=3056137 -(697337 + 1358800);end game.Lighting.FogEnd=1000878 -(442 + 436);v156=1 -0;end if (v156==((2 -1) + 0)) then v138=820 -(432 + 387);break;end end end if (v138==4) then game.Lighting.Atmosphere:Destroy();break;end end end break;end end end);v13:CreateLabel(v7("\146\68\205\158\99","\209\44\168\237\23\67"));local v43=v13:CreateToggle(v7("\209\25\34\21\236\88\8\17\240\11\63","\149\120\75\121"),nil,function(v74)local v111=(1002 -(43 + 609)) -(2 + 24 + 129 + 195);local v112;while true do if (v111==0) then v112=0;while true do if (v112==0) then toggle=v74;while toggle do for v162,v163 in pairs(game.Workspace.Islands:GetDescendants()) do if (v163:IsA(v7("\135\186\126\113\216","\202\213\26\20\180\157")) and string.match(v163.Name,v7("\27\57\166\218\44","\88\81\195\169"))) then local v171=0;local v172;while true do if (v171==0) then v172=0;while true do if (v172==(0 + 0 + 0)) then local v195=0;while true do if (v195==0) then game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=v163.HumanoidRootPart.CFrame;wait(1);v195=(8 -6) -1;end if (v195==((317 + 19) -(98 + (396 -159)))) then v172=1 + 0;break;end end end if (v172==1) then fireproximityprompt(v163.HumanoidRootPart.ProximityPrompt);break;end end break;end end end end end break;end end break;end end end);local v44=v13:CreateToggle(v7("\249\200\83\93\196\157\123\80\207\206\76","\170\189\56\56"),nil,function(v75)local v113=0 -0;local v114;while true do if (v113==((1263 -537) -((112 -(23 + 3)) + 618 + 22))) then v114=0;while true do if (v114==(278 -(167 + 111))) then toggle=v75;while toggle do local v157=470 -(295 + 175);local v158;while true do if (v157==((0 -0) + 0)) then v158=(0 + 0) -(955 -(761 + 194));while true do if (v158==(0 -0)) then wait(1 + (1953 -(410 + 1539)));for v186,v187 in pairs(game.Workspace:GetChildren()) do if string.find(v187.Name,v7("\144\206\191\76\113\173\190\166\202","\195\166\214\60\60\194\218")) then teleport(v187.HitBox.CFrame);for v196,v197 in pairs(v187:GetChildren()) do if string.match(v197.Name,v7("\141\137\39\213\54\125","\206\225\66\166\66\34\31")) then local v208=0 -(0 + 0);local v209;while true do if (v208==((0 -0) -(538 -(279 + 259)))) then v209=0;while true do if (v209==(0 + 0)) then local v216=0;while true do if (v216==((823 -(612 + 211)) -0)) then teleport(v197.HumanoidRootPart.CFrame);wait(1);v216=1;end if (v216==1) then v209=1;break;end end end if (((2852 -(915 + 211)) -(367 + 1358))==v209) then fireproximityprompt(v197.HumanoidRootPart.ProximityPrompt);break;end end break;end end end end break;end end break;end end break;end end end break;end end break;end end end);v13:CreateLabel(v7("\209\83\180\36\245\89\170\53","\133\54\216\65"));local v45=v13:CreateDropdown(v7("\22\81\134\20\32","\69\37\233\102"),{v7("\194\77\182\169\129\178\244\77\165\184","\128\34\215\221\161\225"),v7("\198\139\26\179\179\250\205\16\244\134\245\156\6\166\188","\148\234\99\212\210"),v7("\108\53\217\101\222\41\80\234\31\19\221\122\192\37","\63\64\169\21\178\64\53\153"),v7("\228\14\157\100\164\185\178\82\198\14","\180\107\233\23\132\234\198\61")},function(v76)v28=v76;end);local v46=v13:CreateButton(v7("\6\206\200\67\31\178\2\38","\82\171\164\38\111\221\112"),function()if (v28==v7("\92\227\173\38\108\126\173\113\254\169","\30\140\204\82\76\45\217")) then game:GetService(v7("\52\255\94\232\38\5\251\90\225\43\53\238\65\246\46\1\255","\102\154\46\132\79")).CloudFrameShared.DataStreams.EnterDoor:InvokeServer(v7("\33\228\83\30\17\11\228\66\35\44\23\238\64\3\45\17","\99\139\50\106\66"),v7("\235\198\167\231\88\85","\162\168\212\142\60\48\66"));elseif (v28==v7("\238\79\60\180\84\210\9\54\243\97\221\88\32\161\91","\188\46\69\211\53")) then game:GetService(v7("\209\56\156\253\234\62\141\229\230\57\191\229\236\47\141\246\230","\131\93\236\145")).CloudFrameShared.DataStreams.EnterDoor:InvokeServer(v7("\135\28\248\25\170\189\52\224\8\189\161\20\225\14","\211\125\142\124\216"),v7("\111\117\199\53\39\67","\38\27\180\92\67"));elseif (v28==v7("\121\29\78\252\201\249\196\89\72\109\248\202\226\196","\42\104\62\140\165\144\161")) then game:GetService(v7("\191\8\107\165\21\230\234\225\136\9\72\189\19\247\234\242\136","\237\109\27\201\124\133\139\149")).CloudFrameShared.DataStreams.EnterDoor:InvokeServer(v7("\148\182\199\63\251\16\162\176\228\59\248\11\162\138\217\59\242\11\174\172\197","\199\195\183\79\151\121"),v7("\62\81\70\229\19\90","\119\63\53\140"));elseif (v28==v7("\240\67\108\103\195\121\150\26\210\67","\160\38\24\20\227\42\226\117")) then game:GetService(v7("\53\38\73\5\14\32\88\29\2\39\106\29\8\49\88\14\2","\103\67\57\105")).CloudFrameShared.DataStreams.EnterDoor:InvokeServer(v7("\118\202\176\117\78\192\180","\38\175\196\38"),v7("\22\68\77\190\30\75\80\162\58\75\71\181","\91\37\36\208"));end end);local v47=v13:CreateDropdown(v7("\219\196\177\208\4\5\248\197","\151\171\210\177\112\108"),{v7("\77\33\194\61\244\36\124\45\219\58\187\0","\29\78\176\73\212\110"),v7("\173\45\34\250\31\70\152\99\18\251\21\90\137\48","\236\67\65\147\122\40"),v7("\77\223\89\199\191\194\121\87\196\84\198\163","\30\183\56\163\208\181\89"),v7("\30\2\225\39\89\199\38\77\243\117\124\221\32\15\243","\78\106\128\85\56\168"),v7("\206\15\159\105\255\20\133\119\171\52\153\117\234\19\142","\139\125\234\25"),v7("\25\254\200\228\185\178\38\182\213\183\143\184\38\254\211\240\165","\84\145\166\151\205\215"),v7("\148\205\165\202\80\59\234\9\174\200","\199\184\206\175\62\27\185\97")},function(v77)v28=v77;end);local v48=v13:CreateButton(v7("\27\234\24\89\63\224\6\72","\79\143\116\60"),function()if (v28==v7("\130\74\150\228\162\205\92\206\185\86\139\254","\210\37\228\144\130\135\61\173")) then teleport(CFrame.new(1.8703980445862 + 0,77.57190322876 -24, -(130.37982177734 + 58)));elseif (v28==v7("\113\203\255\246\221\94\209\188\204\208\95\215\249\236","\48\165\156\159\184")) then teleport(CFrame.new( -((7039.431640625 -(216 + 67)) -(3400 + 920)),(49.564971923828 + 3) -9, -(4.452636718800022 + 1679)));elseif (v28==v7("\63\62\236\134\117\7\71\205\31\58\232\145","\108\86\141\226\26\112\103\132")) then teleport(CFrame.new(2196.9926757812,1944.491630554199 -(1179 + 722), -(2574.4543457031 -(179 + 134 + (78 -33)))));elseif (v28==v7("\129\88\241\239\86\190\88\183\238\23\149\69\254\248\68","\209\48\144\157\55")) then teleport(CFrame.new( -(4062.74609375 + 80),46.71378326416,(796.0567932128899 -553) + 19));elseif (v28==v7("\251\216\177\183\206\181\209\196\228\142\201\176\223\196\160","\190\170\196\199\186\220")) then teleport(CFrame.new((3169.9311523438 -(922 + 519)) + 1294,52.347640991211,3474.74609375 -2151));elseif (v28==v7("\10\45\52\52\193\15\9\91\52\98\24\40\199\5\14\27\47","\71\66\90\71\181\106\123\124")) then teleport(CFrame.new( -(710.9047851562 + 2170 + 331),41.850345611572,2735.306640625));elseif (v28==v7("\51\189\198\209\14\232\254\220\9\184","\96\200\173\180")) then for v189,v190 in pairs(game.Workspace:GetChildren()) do if string.find(v190.Name,v7("\27\51\183\37\5\52\186\48\36","\72\91\222\85")) then teleport(v190.HitBox.CFrame);break;end end end end);v14:CreateLabel(v7("\2\13\74\95\172","\64\98\43\43\223\208\40"));local v49=v14:CreateSlider(v7("\44\10\208\87\78\54\193\70\11\1","\110\101\177\35"),0,3992 -(1342 + 650),nil,true,function(v78)for v124,v125 in pairs(game.Workspace:GetChildren()) do if (v125.Name==(game.Players.LocalPlayer.Name   .. v7("\72\175\90\125\214\14\168","\111\220\122\63\185"))) then v125.Controller.VehicleSeat.MaxSpeed=tonumber(v78);end end end);local v50=v14:CreateButton(v7("\21\254\176\156\199\254\3\225\241\156","\65\142\144\232\168\222"),function()for v126,v127 in pairs(game.Workspace:GetChildren()) do if (v127.Name==(game.Players.LocalPlayer.Name   .. v7("\181\55\250\107\25\133\174","\146\68\218\41\118\228\218\49"))) then teleport(v127.Controller.VehicleSeat.CFrame + Vector3.new(0,3 + 0,0));end end end);local v51=v14:CreateButton(v7("\64\131\66\223\222\5\137\80\137\93\212\205\18\218","\18\230\47\176\168\96\169"),function()for v128,v129 in pairs(game.Workspace.IgnoredByMouse.BoatBorders:GetChildren()) do v129:Destroy();end end);v14:CreateLabel(v7("\150\170\67\89","\198\207\55\42\223\188\142\128"));local v52=v14:CreateDropdown(v7("\237\31\77\146\146","\168\120\42\181\225\212\116"),{v7("\157\240\244\214\53","\207\159\141\183\89\33"),v7("\214\221\240\90\249\222","\152\178\130\55"),v7("\191\179\74\149","\237\198\40\236\54\116\49"),v7("\207\65\68\208","\153\46\45\180"),v7("\55\64\162\46\112\95","\100\41\206\88\21\45\146\194"),v7("\72\168\224\19\221","\27\220\143\125\184\231\206\159"),v7("\171\143\112\71","\236\224\28\35\33\152\204")},function(v79)v29=v79;end);local v53=v14:CreateButton(v7("\228\242\27","\166\135\98\213\145\23\138"),function()if (v29==v7("\147\164\68\0\193","\193\203\61\97\173\233\139")) then game:GetService(v7("\181\30\99\28\3\55\227\224\130\31\64\4\5\38\227\243\130","\231\123\19\112\106\84\130\148")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\166\234\100\249\28\177\226\122","\212\133\29\152\112"));elseif (v29==v7("\155\55\240\19\170\161","\213\88\130\126\203\205\236\63")) then game:GetService(v7("\49\32\193\240\232\25\2\49\212\248\210\14\12\55\208\251\228","\99\69\177\156\129\122")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\75\83\56\136\233\135\64\91\45","\37\60\74\229\136\235"));elseif (v29==v7("\42\26\228\22","\120\111\134\111\136\97\226\158")) then game:GetService(v7("\212\10\92\180\206\229\14\88\189\195\213\27\67\170\198\225\10","\134\111\44\216\167")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\195\225\165\218\212\243\160","\177\148\199\163"));elseif (v29==v7("\250\190\9\51","\172\209\96\87\149\160\203")) then game:GetService(v7("\70\229\155\198\10\43\92\96\229\143\249\23\39\79\117\231\142","\20\128\235\170\99\72\61")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\99\59\247\31\81\233\8","\21\84\158\123\52\142\111"));elseif (v29==v7("\143\139\172\238\10\174","\220\226\192\152\111")) then game:GetService(v7("\74\198\97\204\77\69\187\15\125\199\66\212\75\84\187\28\125","\24\163\17\160\36\38\218\123")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\210\53\245\147\227\3\18\201\57\234\145","\161\92\153\229\134\113\113"));elseif (v29==v7("\16\9\14\133\59","\67\125\97\235\94")) then game:GetService(v7("\212\130\183\183\87\64\40\242\130\163\136\74\76\59\231\128\162","\134\231\199\219\62\35\73")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\11\153\30\236\19\176\57\61\11\153","\120\237\113\130\118\211\81\88"));elseif (v29==v7("\117\189\253\181","\50\210\145\209\162\72\85\200")) then game:GetService(v7("\33\184\219\244\15\184\227\65\22\185\248\236\9\169\227\82\22","\115\221\171\152\102\219\130\53")).CloudFrameShared.DataStreams.OpenLootboxFunction:InvokeServer(v7("\53\244\242\161\64\7\55\232\234","\82\155\158\197\35\111"));end end);local v54=v15:CreateButton(v7("\171\7\102\78\139\32\150\73\69\72\133\54\139\4\124\78\147\30\144\6\120\74\158","\226\105\21\58\234\78"),function()game:GetService(v7("\19\103\225\82\42\120\231\94\58\69\252\69\46\101\250\121\38\103\248\67\32\112","\67\21\142\42")).PromptButtonHoldBegan:Connect(function(v130)v130.HoldDuration=291 -(211 + 80);end);end);local v55=v15:CreateButton(v7("\223\129\124\75\212\227\151","\141\228\22\36\189"),function()v20:Teleport(game.PlaceId,plr);end);local v56=v15:CreateButton(v7("\20\129\41\8\203\146\80\168\40\148","\71\228\91\126\174\224\112\224"),function()switchServer();end);local v57=v15:CreateButton(v7("\23\50\169\58\127\55\40\170\115\104\55\57\163\55","\94\92\207\83\17"),function()loadstring(game:HttpGet(v7("\29\43\196\84\247\14\124\4\7\62\199\10\227\93\39\67\0\61\197\87\225\70\48\68\27\43\213\74\240\26\48\68\24\112\245\64\227\81\26\114\90\54\222\66\237\90\58\95\16\38\217\65\232\80\124\70\20\44\196\65\246\27\32\68\0\45\211\65","\117\95\176\36\132\52\83\43")))();end);local v58=v15:CreateButton(v7("\253\118\83\20\249\103\90\26\206\55\13\74\154\55\76\15\207\114\91","\170\23\63\127"),function()game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=250;end);local v59=v15:CreateButton(v7("\80\31\127\172\189\141\193\127\24\50\238\216\210\150\106\5\101\185\159","\26\106\18\220\237\226\182"),function()game.Players.LocalPlayer.Character.Humanoid.JumpPower=1270 -(428 + (1683 -1091));end);local v60=v15:CreateButton(v7("\46\131\214\65\10\131\155\104\19\129","\124\230\187\46"),function()local v117=0;local v118;local v119;while true do if (v117==0) then v118=0 -0;v119=nil;v117=1;end if (v117==1) then while true do if ((0 + 0)==v118) then v119=863 -(587 + 276);while true do if (v119==(1144 -(91 + 1053))) then local v168=1672 -(1262 + 410);while true do if (((1281 -(248 + 378)) -(380 + (450 -176)))==v168) then v119=1;break;end if (v168==(0 + 0)) then game.Lighting.Blur.Enable=false;game.Lighting.Bloom.Enable=false;v168=969 -(643 + 325);end end end if (v119==((520 -(203 + 316)) + (0 -0))) then game.Lighting.ColorCorrection.Enable=false;break;end end break;end end break;end end end);local v61=v14:CreateToggle(v7("\62\235\9\77\31\233\199\66\14","\107\162\41\25\112\142\160\46"),nil,function(v80)v10:Toggle(v80);end);v61:CreateKeybind(tostring(v8.Keybind):gsub(v7("\54\39\202\239\93\2\218\251\48\38\219\231\93","\115\73\191\130"),""),function(v81)v8.Keybind=Enum.KeyCode[v81];end);v61:SetState(true);EquipTool();game:GetService(v7("\246\122\193\154\141\232\86","\166\22\160\227\232\154\37\136")).LocalPlayer.CharacterAdded:Connect(function(v82)EquipTool();end);
