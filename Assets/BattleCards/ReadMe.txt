
 
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


1.) "BattleCards / Prefabs / Cards /"에서 "Card_Template"프리 패브를 찾으십시오.
2.) 빈 장면에 그것을 놓고 캔버스의 자식으로 만듭니다.
3.) "Card_Template"에는 "V_Cards.cs"라는 구성 요소가 있으며, 이름, 통계, 특수 효과, 그래픽 등을 변경합니다.
4.) 카드를 프로젝트 패널로 드래그하여 새로운 프리 패브를 만듭니다.
5.) "BattleCards / Demo / Scenes"에서 "MainMenu"장면을 찾아 엽니다.
6.) 계층 구조 패널에는 "V_CardCollections"스크립트가 포함 된 "Card_Collections"객체가 있으며 이 객체를 선택합니다.
7.) Inspector 패널에서 크기가 6 인 "게임 카드"라는 배열 변수가 표시됩니다. 7로 설정 한 다음 새 카드 프리 패브를 변수의 마지막 요소 슬롯으로 드래그합니다.
8.) 장면을 저장하고 데모를 재생하십시오. 이제 덱 편집기를 통해 게임에서 새 카드에 액세스 할 수 있습니다

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