
########### next target ###############

SET(game_STAT_SRCS
   AccountMgr.cpp
   AccountMgr.h
   AddonMgr.cpp
   AddonMgr.h
   AchievementMgr.h
   AchievementMgr.cpp
   AddonHandler.cpp
   AddonHandler.h
   CombatAI.cpp
   CombatAI.h
   ArenaTeam.cpp
   ArenaTeam.h
   ArenaTeamHandler.cpp
   AuctionHouseHandler.cpp
   AuctionHouseBot.cpp
   AuctionHouseBot.h
   AuctionHouseMgr.cpp
   AuctionHouseMgr.h
   Bag.cpp
   Bag.h
   BattleGround.cpp
   BattleGroundAA.cpp
   BattleGroundAB.cpp
   BattleGroundABG.cpp
   BattleGroundAV.cpp
   BattleGroundBE.cpp
   BattleGroundDS.cpp
   BattleGroundEY.cpp
   BattleGroundIC.cpp
   BattleGroundNA.cpp
   BattleGroundRL.cpp
   BattleGroundRV.cpp
   BattleGroundSA.cpp
   BattleGroundWS.cpp
   BattleGround.h
   BattleGroundAA.h
   BattleGroundAB.h
   BattleGroundABG.h
   BattleGroundAV.h
   BattleGroundBE.h
   BattleGroundDS.h
   BattleGroundEY.h
   BattleGroundIC.h
   BattleGroundNA.h
   BattleGroundRL.h
   BattleGroundRV.h
   BattleGroundSA.h
   BattleGroundWS.h
   BattleGroundHandler.cpp
   BattleGroundMgr.cpp
   BattleGroundMgr.h
   Calendar.cpp
   Calendar.h
   CalendarHandler.cpp
   Cell.h
   CellImpl.h
   Channel.cpp
   Channel.h
   ChannelHandler.cpp
   CharacterHandler.cpp
   ChannelMgr.h
   ChannelMgr.cpp
   Chat.cpp
   Chat.h
   ChatHandler.cpp
   CombatHandler.cpp
   ConfusedMovementGenerator.cpp
   ConfusedMovementGenerator.h
   Corpse.cpp
   Corpse.h
   CreatureAI.cpp
   CreatureAI.h
   CreatureAIFactory.h
   CreatureAIImpl.h
   CreatureAIRegistry.cpp
   CreatureAIRegistry.h
   CreatureAISelector.cpp
   CreatureAISelector.h
   CreatureEventAI.cpp
   CreatureEventAIMgr.cpp  
   Creature.cpp
   Creature.h
   CreatureGroups.cpp
   CreatureGroups.h
   DBCEnums.h
   DBCStores.cpp
   DBCStores.h
   DBCStructure.h
   DBCfmt.h
   Debugcmds.cpp
   DestinationHolder.cpp
   DestinationHolder.h
   DestinationHolderImp.h
   DuelHandler.cpp
   DynamicObject.cpp
   DynamicObject.h
   FleeingMovementGenerator.cpp
   FleeingMovementGenerator.h
   Formulas.h
   GameEventMgr.cpp
   GameEventMgr.h
   GameObject.cpp
   GameObject.h
   GlobalEvents.cpp
   GlobalEvents.h
   GossipDef.cpp
   GossipDef.h
   GridDefines.h
   GridNotifiers.cpp
   GridNotifiers.h
   GridNotifiersImpl.h
   GridStates.cpp
   GridStates.h
   Group.cpp
   Group.h
   GroupHandler.cpp
   GuardAI.cpp
   GuardAI.h
   Guild.cpp
   Guild.h
   GuildHandler.cpp
   HomeMovementGenerator.cpp
   HomeMovementGenerator.h
   HostileRefManager.cpp
   HostileRefManager.h
   IdleMovementGenerator.cpp
   IdleMovementGenerator.h
   InstanceData.cpp
   InstanceData.h
   InstanceSaveMgr.cpp
   InstanceSaveMgr.h
   Item.cpp
   Item.h
   ItemEnchantmentMgr.cpp
   ItemEnchantmentMgr.h
   ItemHandler.cpp
   ItemPrototype.h
   Language.h
   Level0.cpp
   Level1.cpp
   Level2.cpp
   Level3.cpp
   LFGHandler.cpp
   LootHandler.cpp
   LootMgr.cpp
   LootMgr.h
   Mail.cpp
   Mail.h
   Map.cpp
   Map.h
   MapInstanced.cpp
   MapInstanced.h
   MapManager.cpp
   MapManager.h
   MapUpdater.cpp
   MapUpdater.h
   MapReference.h
   MapRefManager.h
   MiscHandler.cpp
   MotionMaster.cpp
   MotionMaster.h
   MovementGenerator.cpp
   MovementGenerator.h
   MovementGeneratorImpl.h
   MovementHandler.cpp
   NPCHandler.cpp
   NPCHandler.h
   PassiveAI.cpp
   PassiveAI.h
   ObjectAccessor.cpp
   ObjectAccessor.h
   Object.cpp
   ObjectDefines.h
   ObjectGridLoader.cpp
   ObjectGridLoader.h
   Object.h
   ObjectMgr.cpp
   ObjectMgr.h
   ObjectPosSelector.cpp
   ObjectPosSelector.h
   Opcodes.cpp
   Opcodes.h
   OutdoorPvP.cpp
   OutdoorPvP.h
   OutdoorPvPEP.cpp
   OutdoorPvPEP.h
   OutdoorPvPHP.cpp
   OutdoorPvPHP.h
   OutdoorPvPMgr.cpp
   OutdoorPvPMgr.h
   OutdoorPvPNA.cpp
   OutdoorPvPNA.h
   OutdoorPvPSI.cpp
   OutdoorPvPSI.h
   OutdoorPvPTF.cpp
   OutdoorPvPTF.h
   OutdoorPvPZM.cpp
   OutdoorPvPZM.h
   Path.h
   PetAI.cpp
   PetAI.h
   Pet.cpp
   Pet.h
   PetHandler.cpp
   PetitionsHandler.cpp
   Player.cpp
   Player.h
   PlayerDump.cpp
   PlayerDump.h
   PointMovementGenerator.cpp
   PointMovementGenerator.h
   PoolHandler.cpp
   PoolHandler.h
   QueryHandler.cpp
   QuestDef.cpp
   QuestDef.h
   QuestHandler.cpp
   RandomMovementGenerator.cpp
   RandomMovementGenerator.h
   ReactorAI.cpp
   ReactorAI.h
   ReputationMgr.cpp
   ReputationMgr.h
   ScriptedSmartAI.cpp
   ScriptedSmartAI.h
   ScriptLoader.cpp
   ScriptLoader.h
   ScriptMgr.cpp
   ScriptMgr.h
   ScriptSystem.cpp
   ScriptSystem.h
   SharedDefines.h
   SkillHandler.cpp
   SpellAuraDefines.h
   SpellAuras.cpp
   SpellAuras.h
   SpellAuraEffects.cpp
   SpellAuraEffects.h
   Spell.cpp
   SpellEffects.cpp
   Spell.h
   SkillDiscovery.cpp
   SkillDiscovery.h
   SkillExtraItems.cpp
   SkillExtraItems.h
   SpellHandler.cpp
   SocialMgr.cpp
   SocialMgr.h
   SpellMgr.cpp
   SpellMgr.h
   StatSystem.cpp
   TargetedMovementGenerator.cpp
   TargetedMovementGenerator.h
   TaxiHandler.cpp
   TemporarySummon.cpp
   TemporarySummon.h
   TicketHandler.cpp
   Tools.cpp
   Tools.h
   TotemAI.cpp
   TotemAI.h
   Totem.cpp
   Totem.h
   TradeHandler.cpp
   Transports.cpp
   Transports.h
   ThreatManager.cpp
   ThreatManager.h
   Traveller.h
   Unit.cpp
   Unit.h
   UnitAI.cpp
   UnitAI.h
   UnitEvents.h
   UpdateData.cpp
   UpdateData.h
   UpdateFields.h
   UpdateMask.h
   Vehicle.cpp
   Vehicle.h
   VoiceChatHandler.cpp
   WaypointManager.cpp
   WaypointManager.h
   WaypointMovementGenerator.cpp
   WaypointMovementGenerator.h
   Weather.cpp
   Weather.h
   World.cpp
   World.h
   WorldLog.cpp
   WorldLog.h
   WorldSession.cpp
   WorldSession.h
   WorldSocket.cpp
   WorldSocket.h
   WorldSocketMgr.cpp
   WorldSocketMgr.h
   FollowerReference.cpp
   FollowerReference.h
   FollowerRefManager.h
   GroupReference.cpp
   GroupReference.h
   GroupRefManager.h
   OutdoorPvPImpl.h
   ZoneScript.h
)

if(NOT DO_SCRIPTS)
   SET(game_STAT_SRCS ${game_STAT_SRCS}
      ScriptedEscortAI.cpp
      ScriptedEscortAI.h
      ScriptedPch.cpp
      ScriptedPch.h
      ScriptedCreature.cpp
      ScriptedCreature.h
      ScriptedFollowerAI.cpp
      ScriptedFollowerAI.h
      ScriptedGossip.h
      ScriptedGuardAI.cpp
      ScriptedGuardAI.h
      ScriptedInstance.h
      ScriptedSimpleAI.cpp
      ScriptedSimpleAI.h
   )
   message("-- Added Script Engine to GAME lib")
endif(NOT DO_SCRIPTS)

add_library(game STATIC ${game_STAT_SRCS})
ADD_DEPENDENCIES(game revision.h)

