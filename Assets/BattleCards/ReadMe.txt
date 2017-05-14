
 
               BATTLECARDS
     Collectibe Card Game Starter Kit

         Visyde Interactives 2016

/////////////////////////////////////////////////////
Thank you for purchasing this asset!
/////////////////////////////////////////////////////

This is will guide you through developing your next
card game with this kit.

Please follow this guide to fully understand the kit.

/////////////////////////////////////////////////////

This kit features:

- Full AI opponent
- Deck customization (Save & Load)
- Easy-to-customize card templates
- Lot's of card stats combinations
- Ready-made spell card effect logics
- Fully documented code
- Tooltip system and Custom Tooltips!

/////////////////////////////////////////////////////

*NOTE: Add all the demo scenes to the build settings
       before playing.


GAMEPLAY:

- Each player has a base (which is the one you have to defend), a 
  battle zone, a spell zone, and a hand zone.
- Try to defeat the opponent's base by deploying cards.
- Creature cards are deployed in the battle zone while spell cards
  are only in the spell zone.
- Your energy decreases as you deploy or draw cards.
- Every player draws 1 free card for every turn.
- Some creature cards can attack cards, some are only for the base,
  and some can attack both.
- Spell cards are activated automatically and cannot target cards.

/////////////////////////////////////////////////////

HOW TO MAKE A NEW CARD:

1.) Locate the "Card_Template" prefab under "BattleCards/Prefabs/Cards/".
2.) Place it in an empty scene, and make it a child of a canvas.
3.) The "Card_Template" has a component called "V_Cards.cs",
    change the name, stats, extra effects, graphics, etc.
4.) Make a new prefab of the card by dragging it to the
            project panel.
5.) Locate and open the "MainMenu" scene under "BattleCards/Demo/Scenes".
6.) In the Hierarchy panel, there is a "Card_Collections" object
    which contains the "V_CardCollections" script, select it.
7.) Now, in the Inspector panel you will see an array variable 
    called "Game Cards" which has a size of 6. Make it 7 then drag
    your new card prefab to the last element slot of the variable.
8.) Save the scene and play the demo. You can now access the new
    card in game via Deck Editor.


1.) "BattleCards / Prefabs / Cards /"���� "Card_Template"���� �к긦 ã���ʽÿ�.
2.) �� ��鿡 �װ��� ���� ĵ������ �ڽ����� ����ϴ�.
3.) "Card_Template"���� "V_Cards.cs"��� ���� ��Ұ� ������, �̸�, ���, Ư�� ȿ��, �׷��� ���� �����մϴ�.
4.) ī�带 ������Ʈ �гη� �巡���Ͽ� ���ο� ���� �к긦 ����ϴ�.
5.) "BattleCards / Demo / Scenes"���� "MainMenu"����� ã�� ���ϴ�.
6.) ���� ���� �гο��� "V_CardCollections"��ũ��Ʈ�� ���� �� "Card_Collections"��ü�� ������ �� ��ü�� �����մϴ�.
7.) Inspector �гο��� ũ�Ⱑ 6 �� "���� ī��"��� �迭 ������ ǥ�õ˴ϴ�. 7�� ���� �� ���� �� ī�� ���� �к긦 ������ ������ ��� �������� �巡���մϴ�.
8.) ����� �����ϰ� ���� ����Ͻʽÿ�. ���� �� �����⸦ ���� ���ӿ��� �� ī�忡 �׼��� �� �� �ֽ��ϴ�

HOW TO CHANGE THE GAME ELEMENTS:

1.) Locate the "InGame" scene under "BattleCards/Demo/Scenes".
2.) There is a game object called "GAME_MANAGER", select it.
3.) In the inspector panel, you will see a component called
    "V_GameManager" which holds all the data for the current
    level/game.
4.) Change the values in it and save the scene.
5.) Go to the "MainMenu" scene, hit play and enjoy.

/////////////////////////////////////////////////////

Changelog:

*1.0: 
	First release!

*1.1: 
	-Fixed some errors in the ReadMe file.
	-Changed some stats of the demo cards for more balanced gameplay.
	-Improved the game screen.
	-Improved some scripts.