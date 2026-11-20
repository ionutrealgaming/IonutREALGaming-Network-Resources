# Ionuț REAL Gaming Network — Project Plan

> **Project status:** Development and planning  
> **Network status:** Offline since 31 August 2026  
> **Relaunch target:** Not confirmed. The current planning window is 25 December 2026 – 15 January 2027.  
> **Guiding motto:** **Fără moduri pe client** — players should not need client-side mods. A resource pack may be offered; gameplay systems are intended to work without requiring client mods.

This document describes the **player-facing mechanics and intended experience** of Ionuț REAL Gaming Network. It deliberately does not document the technical implementation, software choices, plugins, scripts, source-code changes, hosting setup, or development architecture.

Some values and rules below are still proposals and may change before release.

---

## 1. Network vision

Ionuț REAL Gaming Network is intended to be a varied Minecraft multiplayer network with a strong community identity. It should offer more than one type of gameplay: relaxed survival, social and economic activity, competitive events, special limited-time experiences, and minigames.

The network should remain playable and enjoyable while new features are introduced gradually. The relaunch is intended to restore the network to the state it had before its closure; new features and updates are planned to arrive progressively after the return.

### Core principles

- **No client-side mod requirement:** players should be able to join without installing gameplay mods.
- **Minecraft should still feel like Minecraft:** custom mechanics should complement the vanilla experience rather than replace it.
- **Reward activity:** playing, building, farming, competing, trading, and cooperating should all have value.
- **Community first:** social interaction, teamwork, trading, and friendly competition matter.
- **Freedom with boundaries:** players should have meaningful freedom, while cheating, exploits, and harassment remain unacceptable.

---

# 2. Survival

Survival is intended to be the network's main long-term gameplay experience: familiar Minecraft survival with extra systems that reward activity and create reasons to return.

## 2.1 Survival philosophy and world rules

- The experience should remain close to vanilla Minecraft.
- The day/night cycle should last longer than the default cycle.
- There will be **no land claims and no protected player bases**.
- Players can build freely, form teams, raid, compete, and interact with other players.
- The server should feel relaxed overall, even though PvP and raids can create risk.
- Cheats, hacks, exploits, and harassment are not accepted.

### Controlled anarchy

Survival aims for controlled anarchy rather than a fully protected or completely lawless world.

- Rival teams may fight, raid one another, steal resources, and compete.
- Staff should not interfere in every ordinary rivalry or legitimate raid.
- Destructive behaviour whose purpose is simply to ruin another player's progress, persistent harassment, or conduct that drives people away may be investigated.
- Reports should be reviewed in context. A report is a reason to investigate, not automatic proof of wrongdoing.
- Evidence, witnesses, and the history of the incident should matter.

The guiding distinction is: **Rivalry is welcome. Harassment isn't.**

### Proposed consequences for griefing and theft

The current proposal is a graduated response:
1. A first confirmed incident may result in severe temporary in-game effects, such as Slowness and Blindness for a specified amount of online time.
2. Repeated incidents may lead to deductions from the player's balance.
3. Continued behaviour may lead to temporary bans.

The exact duration, thresholds, and process are not final. The current philosophy is to avoid permanent bans and to distinguish legitimate gameplay from abusive behaviour.

## 2.2 Economy

The in-game currency is the **lei**.

The economy should reward different kinds of activity instead of making one farm or strategy overwhelmingly profitable.

Planned ways to earn money include:
- Jobs.
- Player kills.
- Quests.
- Raids.
- Events.
- Player-to-player trading.
- Other Survival activities.

The server shop should offer relatively few items or charge high prices, so that players still have a reason to gather and craft items themselves. Selling items through the sell system should provide relatively low returns.

### Leaderboards

Planned leaderboards include:
- Balance.
- Kills.
- Jobs.
- BlockBall.
- Bosses.
- Quests.
- Playtime.
- Events.
- Trading.

## 2.3 Raids

Raids are intended to be relatively rare activities involving Pillagers.

- Players may participate alongside Pillagers in raids against villages.
- Players who turn against the Pillagers and defeat them without dying may receive **Despicable Points** and substantial money or other rewards.
- Raids may occur at villages and, on rare occasions, at player bases.

The exact frequency, rewards, and conditions are still to be determined.

## 2.4 Boss fights

Survival will include boss encounters with different levels of difficulty or progression.

Defeating bosses will provide rewards and money. The final boss roster, progression, and reward values have not yet been decided.

## 2.5 Special Missions

Special Missions are intended to be rare activities with cooldowns, not the main way to play Survival.

Possible mission objectives include:
- Defeating specific mobs.
- Retrieving objects.
- Surviving waves of enemies.
- Defeating a boss within a time limit.

Missions provide rewards for completing their objectives. They are standalone activities, not part of the Story Mode.

## 2.6 BlockBall

BlockBall is a football activity intended to host relatively frequent larger events.

Possible event rewards include:
- Money.
- Benefits.
- Titles.
- Cosmetics.
- Crate keys.
- Battle Pass points.
- Trophies.

Player or team rankings may also be included.

## 2.7 Survival Duels

Survival Duels are optional player-arranged fights within Survival. They are separate from any dedicated Duels minigame.

Players may agree to wager money or items, such as a Mace or items from their inventories. The participants decide the terms before accepting the duel. Participation is voluntary.

## 2.8 Just PvP Events

Just PvP is an event in which participants enter with their **real Survival inventories**.

Intended sequence:
1. Participants enter the event with their current inventories.
2. PvP is enabled and the event timer begins.
3. Players fight; a player who dies can lose the items they brought.
4. When the timer expires, PvP is disabled.
5. The remaining players get a limited period to collect items dropped during the event.
6. Players may place shulker boxes and store collected loot in them.
7. Players cannot open another participant's shulker box.
8. When the collection period ends, participants are returned to where they were before the event, with the items they collected. Unopened shulkers travel with their owners.

The exact timers and safe handling of full inventories still need to be finalized. The intended experience is to make the event high-risk and exciting without accidentally losing a player's items due to inventory limits.

## 2.9 Player trading

Players should be able to trade directly with one another.

Trading may happen through a trading interface or through manually dropping and exchanging items. Trading outside the Trading Plaza is possible but carries the ordinary risks of arranging a trade in the open world.

## 2.10 Trading Plaza

The Trading Plaza is designed as a **cafeteria-like meeting place**, not a mall or a collection of player-owned shops.

- It behaves like Survival, including manual item exchanges.
- PvP is disabled inside the Plaza.
- Items dropped for an exchange cannot be stolen by unrelated players.
- The Plaza contains enclosed private cabins for two players to negotiate and trade.
- When players enter a cabin together, their conversation is treated as a private message between them.
- The cabins are intended to prevent other players from seeing or hearing the exchange.

### Trade confirmation and cancellation

If either participant tries to leave the cabin or exit the trade, a confirmation prompt appears:

**“Are you sure about this trade?”**

- **YES:** confirms leaving. The trade remains as it currently stands.
- **NO:** cancels the entire trade, whether the participants used the trading interface or manual item drops. All exchanged items are returned to their original owners.

The intended rule is a complete rollback: both participants should end up with the items they owned before the trade began.

## 2.11 Community Shop Area

The Community Shop Area gives players places to create and operate shops.

- Each player may have a plot.
- A player may build their own shop or purchase a plot with a prebuilt shop.
- Plots may be sold or resold.
- Shops may be built by players or supplied by the server/team.
- Chests can offer items in exchange for money or other items.
- Shop owners collect their earnings manually using `/collect`.
- There is no planned rent or tax.

### Plot prices and resale

- Empty plots have a fixed price of **5 in-game lei**.
- Built plots have a variable value depending on who built them, what was built, and the quality or complexity of the construction.

When selling a plot, the owner has three choices:
1. Demolish the construction manually.
2. Request automatic demolition for **10 in-game lei**.
3. Sell the plot with the construction still present.

## 2.12 Other Survival features

Planned additional features include:
- **Chat bubbles:** messages can appear above players' heads.
- **AFK rewards:** rewards for qualifying AFK time; exact rules are not yet specified.
- **Playtime rewards:** rewards for accumulated playtime.
- **Battle Pass:** a progression and reward track.
- **Crates:** event- and update-exclusive items and rewards.

The **Global Rewards** system is network-wide and is not exclusive to Survival.

## 2.13 Combat Log

Combat Log is intended to prevent players from escaping an active player-versus-player fight by disconnecting or using commands.

- It activates **only when another player hits you**.
- Damage from mobs, the environment, falls, lava, and other non-player sources does not activate it.
- While Combat Log is active, **no commands may be used**.

The exact duration and disconnect consequences remain to be specified.

## 2.14 Bounty System

The Bounty System creates high-stakes player hunts, with rewards for both the person placing the bounty and the target who manages to survive.

### Placing a bounty

- A player must have at least **15 hours of Survival playtime** before placing a bounty.
- The minimum bounty amount is **5,000 lei**.
- After placing a bounty, that player must accumulate another **50 hours of playtime** before placing another one. The cooldown starts when the previous bounty is placed; offline time does not count.
- A target must have at least **2 hours of Survival playtime** to be eligible.

### Target rewards while hunted

- Every time the target kills another player, they receive **2× the amount of their current bounty**.

### Rewards when the target dies

When the target dies, the current proposal is:
- Their inventory is reset.
- Their balance is reset.
- They still receive rewards for the time they survived while carrying the bounty.

The survival rewards are based on activity during that bounty period:
- **Diamonds:** based on the number of kills made during the bounty period, up to a maximum of **30 diamonds**.
- **Netherite:** based on survival time:
  - At 3 hours survived: 1 Netherite.
  - Every additional 4 hours: +1 Netherite.
  - Maximum: 10 Netherite.

Only online playtime counts toward the survival duration. Offline time does not count.

The exact death conditions, reward calculation edge cases, and anti-abuse rules still need to be finalized.

## 2.15 Roulette

Players may use the Roulette once every **15 hours of playtime**.

- Every possible result should be a useful or good item.
- Some results should be especially valuable and rare.
- The cooldown is intended to keep Roulette from becoming too frequent.

The reward pool, odds, and exact playtime rules are not yet specified.

## 2.16 Launch custom food content

The currently planned custom food content for the Survival launch includes:
- **Josh's More Foods**.
- **More Food**.

These additions are intended to expand food variety while keeping the core Survival experience recognizable.

---

# 3. Survival Team System

Teams should be more than temporary PvP alliances. They should have shared progression, economic activity, and goals.

## 3.1 Team progression

- Teams have levels.
- Teams have their own **Team Battle Pass**, separate from the regular Battle Pass available to all players.
- Teams can complete Team Quests.
- Teams can participate in Team Jobs.

### Online team activity rewards

When a player is online and at least one other member of their team is also online, the player receives:
- **0.01 lei per minute**.
- **10 TeamPass XP per minute**.

These rewards are intended to encourage active teamwork.

## 3.2 Company System

The Company System is connected to Team Jobs and gives teams a way to organize shared or individual businesses.

A team can choose between two business models:

### Option A — Team Shop

The company operates one shared Team Shop that teammates can access and work on together.

### Option B — Individual shops and jobs

Each member has their own individual shop and job, with a bonus for being part of a team.

### Company boss reward

The company boss receives a bonus based on the number of members who have jobs in the company:

- **10 lei × the number of members with company jobs**.
- Paid once every **3 hours**.

Example: if five members have jobs in the company, the boss receives 50 lei every three hours.

Whether the boss must also have a job is not yet finalized.

---

# 4. Network-wide systems

These systems are intended to apply across the network rather than belonging only to Survival.

## 4.1 Global Rewards

Global Rewards is a network-wide reward concept. Its exact triggers, reward pool, and schedule still need to be defined.

## 4.2 Network identity and community

The network should support social interaction and a recognizable shared identity across its different game modes and events.

---

# 5. Survival Events

The current planned launch order for the three special Survival events is:

1. **OG Craft**
2. **Unstable SMP**
3. **Rick and Morty**

These events add special content and experiences to Survival. Their detailed schedules and availability are not yet confirmed.

## 5.1 Event One — OG Craft

OG Craft brings back the look and feel of older Minecraft items and blocks.

### Separate OG blocks

The planned OG blocks are separate from their modern counterparts:
- OG Glass.
- OG Oak Wood.
- OG Oak Planks.

### OG gear

The planned old-style gear includes:
- Leather armour.
- Chainmail armour.
- Iron armour.
- Gold armour.
- Diamond armour.
- Wooden, Stone, Iron, Gold, and Diamond swords.
- An OG Bow.

The old-style items are intended to exist separately from their modern versions.

### Classic Season and crafting

- OG gear and blocks are intended to be craftable permanently.
- The special materials required to craft them are available only during the separate **Classic Season**.
- The currently named material categories are Wood, Stone, Iron, Gold, and Diamond.

The detailed acquisition and crafting rules for these special materials have not yet been documented.

## 5.2 Event Two — Unstable SMP

Unstable SMP adds special references and items inspired by the Unstable SMP / Unstable Universe content.

Currently planned items:
- **Orbital Strike Cannon Rod**.
- **Special Spyglass**, a reference to the Parrot and Wifies story.

The Special Spyglass is intended as an Easter egg and a meaningful reference to the events involving Parrot and Wifies.

The exact in-game behaviour, availability, and balance of these items are still to be specified.

## 5.3 Event Three — Rick and Morty

The currently planned item for this event is the **Portal Gun**.

No other event mechanics have been confirmed yet.

---

# 6. Relaunch and update approach

The relaunch is intended to bring back the network **as it was before it closed on 31 August 2026**.

The current target window being considered is **25 December 2026 – 15 January 2027**, but no exact reopening date has been confirmed.

The intended approach is:
- Restore the previous network experience for the relaunch.
- Keep the network online while development continues.
- Add new features and improvements gradually after reopening.
- Do not require every future feature to be finished before the network can return.
- New minigames may arrive before Summer 2027, but this is not a promise or fixed deadline.
- Larger updates may be planned for Summer 2027, depending on development progress and real-life availability.

---

# 7. Open decisions and items to finalize

The following details remain open and should not be treated as final rules:

- Exact reopening date.
- Minecraft version and final gameplay balance.
- Survival day/night duration.
- Economy prices, job rewards, quest rewards, and activity payouts.
- Raid frequency, boss roster, and boss rewards.
- Special Mission cooldowns and reward values.
- BlockBall event schedule and reward details.
- Just PvP timers and inventory overflow handling.
- Trading Plaza edge cases, including full inventories during a cancelled trade.
- Community plot availability and the valuation of built plots.
- AFK reward rules and Playtime reward milestones.
- Battle Pass progression and reward tracks.
- Combat Log duration and disconnect consequences.
- Bounty death conditions, exact reward calculations, and anti-abuse rules.
- Roulette reward pool and probabilities.
- Classic Season schedule and the full OG crafting-material system.
- Unstable SMP item behaviour.
- Rick and Morty event details beyond the Portal Gun.
- Global Rewards triggers and rewards.

---

*This is a living design document. It records the intended player-facing experience, not a promise that every listed feature will be available on relaunch day. Rules may be adjusted during development and testing.*
