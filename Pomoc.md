## Komnedy gracza (Aby gracz miał dostęp do wszystkich poniższych komend nadaj mu uprawnienie: afterowegildie.player)
```yaml
/g sojusz (tag gildii) - Zawiera sojusz z gildią (uprawnienie: afterowegildie.alliance)
/g zaloz (tag gildii) (nazwa gildii) - Tworzy nową gildie (uprawnienie: afterowegildie.create)
/g usun - Usuwa gildie (uprawnienie: afterowegildie.delete)
/g powieksz - Powiększa teren gildii (uprawnienie: afterowegildie.enlarge)
/g dom - Teleportacja do bazy gildii (uprawnienie: afterowegildie.home)
/g info (tag) - Informacje na temat gildii (uprawnienie: afterowegildie.info)
/g zapros (gracz) - Wysyła zaproszenie do gildii (uprawnienie: afterowegildie.invite
/g itemy - Pokazuje przedmioty potrzebne do założenia gildii (uprawnienie: afterowegildie.items)
/g dolacz (tag gildii) - Dołącza do gildii (uprawnienie: afterowegildie.join)
/g wyrzuc (gracz) - Wyrzuca gracza z gildii (uprawnienie: afterowegildie.kick)
/g lider (gracz) - Oddaje właściciela gildii innej osobie (uprawnienie: afterowegildie.leader)
/g opusc - Opuszcza gildie (uprawnienie: afterowegildie.leave)
/g uprawnienia (gracz) - Zarządzanie uprawnieniami gracza (uprawnienie: afterowegildie.permissions)
/g pvp - Włącza lub wyłącza pvp w gildii (uprawnienie: afterowegildie.pvp)
/g sethome - Ustawia dom gildii (uprawnienie: afterowegildie.sethome)
/g spvp - Włącza lub wyłącza pvp w sojuszu gildii (uprawnienie: afterowegildie.spvp)
/g magazyn - Otwiera magazyn gildii (uprawnienie: afterowegildie.treasure)
/g przedluz - Przedłuża ważność gildii (uprawnienie: afterowegildie.validity)
/g zastepca (Gracz) - Daje zastępce właściciela graczowi (uprawnienie: afterowegildie.vleader)
```
## Komnedy administratora (Aby gracz miał dostęp do wszystkich poniższych komend nadaj mu uprawnienie: afterowegildie.admin)
```yaml
/ag dodaj (gracz) (tag gildii) - Dodaje gracza do gildii (uprawnienie: afterowegildie.admin.add)
/ag zycia (tag gildii) (ilość żyć) - Ustawia życia gildii (uprawnienie: afterowegildie.admin.addlives)
/ag zakladanie - Włącza lub wyłącza możliwość zakładania gildii (uprawnienie: afterowegildie.admin.allowcreate)
/ag ban (tag gildii) (powód) - Banuje gildie (uprawnienie: afterowegildie.admin.ban)
/ag usun (tag gildii) - Usuwa gildie (uprawnienie: afterowegildie.admin.delete)
/ag wyrzuc (gracz) - Wyrzuca gracza z jego gildii (uprawnienie: afterowegildie.admin.kick)
/ag reload - Przeładowanie konfiguracji pluginu (uprawnienie: afterowegildie.admin.reload)
/ag ustawitemy - Ustawia przedmioty potrzebne do zalożenia gildii (uprawnienie: afterowegildie.admin.setitems)
/ag tnt - Włącza lub wyłącza ekspozje od tnt na terenie gildii (uprawnienie: afterowegildie.admin.tnt)
/ag tp (tag gildii) - Teleportuje do domu gildii (uprawnienie: afterowegildie.admin.tp)
```
## Placeholdery: (Wymagany plugin [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/))
```yaml
%afterowegildie_points% - ilość punktów
%afterowegildie_kills% - ilość zabójstw
%afterowegildie_deaths% - ilość śmierci
%afterowegildie_position% - pozycja w rankingu
%afterowegildie_top_user_points_1% - pozycja gracza w rankingu na miejscu 1
%afterowegildie_top_guild_points_1% - pozycja gildii w rankingu na miejscu 1
%afterowegildie_guild_name% - nazwa gildii do której należysz
%afterowegildie_guild_tag% - tag gildii do której należysz
%afterowegildie_guild_members% - ilość członków w gildii
%afterowegildie_guild_created% - data kiedy gildia została stworzona
%afterowegildie_guild_validity% - data do kiedy gildia jest ważna
afterowegildie_guild_lives% - życia gildii
%afterowegildie_guild_size% - rozmiar gildii
%afterowegildie_guild_points% - punkty gildii
%afterowegildie_guild_kills% - zabójstwa gildii
%afterowegildie_guild_deaths% - śmierci gildii
```
