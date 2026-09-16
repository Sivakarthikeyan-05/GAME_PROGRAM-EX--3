# GAME_PROGRAM-EX--3

### NAME    : Sivakarthikeyan V

### REG. NO.: 212225220098

---

# EXP: 3

## Replacing the Default Third-Person Character Mesh and Applying New Animations Using an Animation Blueprint

## Aim

To replace the default third-person character mesh with a custom **Skeletal Mesh** and apply new animations using an **Animation Blueprint** in Unreal Engine.

---

## Procedure

### 1. Import New Character Mesh and Animations

* Open the **Content Browser**.
* Import a new **Skeletal Mesh** along with its **Animations** using FBX files.
* Ensure that the mesh is rigged correctly.
* The character should ideally use the **UE4 Mannequin Skeleton** or a skeleton compatible with it.

---

### 2. Replace Character Mesh

* Open the **ThirdPersonCharacter Blueprint**.
* It is usually located in:

`ThirdPersonBP/Blueprints`

* Select the **Mesh** component.
* In the **Details Panel**, change the **Skeletal Mesh** property to the newly imported custom character mesh.

---

### 3. Set the Animation Blueprint

* If a matching **Animation Blueprint** is already available, assign it in the **Details Panel** under the **Animation** section.

### If an Animation Blueprint is Not Available

Create a new Animation Blueprint by following these steps:

1. Right-click in the **Content Browser**.
2. Select:

`Animation → Animation Blueprint`

3. Choose the correct skeleton for the imported character.
4. Open the newly created Animation Blueprint.
5. In the **AnimGraph**, create and configure:

   * State Machines
   * Idle Animation
   * Walk Animation
   * Run Animation
   * Transition Rules
6. Connect the animation states according to the character's movement.
7. Compile and save the Animation Blueprint.

---

### 4. Preview and Test

* Place the character in the level.
* Press the **Play** button.
* Test the following character animations:

  * Idle
  * Walking
  * Running

Verify that the animations change correctly according to the character's movement.

---

## Output

![Custom Character Mesh](https://github.com/user-attachments/assets/da92e5cf-9199-4e45-90e3-697916a28716)

<br>

![Character Animation Setup](https://github.com/user-attachments/assets/98c10596-d453-4b40-b1c9-6fd5630b63ac)

<br>

![Character Animation Output](https://github.com/user-attachments/assets/b8b2a3ec-eab5-44a2-9213-097a6d7f7845)

---

## Result

Thus, the default third-person character mesh was successfully replaced with a custom **Skeletal Mesh**, and new character animations were successfully applied using an **Animation Blueprint** in Unreal Engine.

The character was successfully tested with **Idle, Walking, and Running** animations.
