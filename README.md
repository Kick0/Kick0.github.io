Relational Pain Architecture: From Biological Nociception to Emergent Phantom Limb Pathology in Active-Inference AI

Date: November 26, 2026

Project Type: Computational Neuroscience & Embodied AI Investigation

Companion Live Web Lab: index.html

Abstract

This report documents an end-to-end theoretical and empirical investigation into the nature of pain, pleasure, and host-signal interpretation across biological and artificial systems. Starting from the hypothesis that affective states depend on central host framing rather than intrinsic properties of peripheral nerve impulses, we trace how mammalian nervous systems separate upstream edge threat detection (nociception) from downstream central evaluation (pain).

To test whether pain-like pathology can emerge purely from predictive architecture without hardcoded rules, we constructed an embodied dual-arm active-inference neural agent ($9 \rightarrow 16 \rightarrow 4$ multi-layer perceptron forward body model) and subjected it to a six-stage surgical and environmental benchmark. Experimental telemetry demonstrates two primary findings:

Emergent Functional Phantom Pain: Severing an actuator-sensor channel while preserving frozen body-map priors locks the agent into a $100\%$ motor cramp, generates a $97\%$ host salience alarm, and degrades healthy-limb task efficiency from $97\%$ down to $31\%$.

Host-Signal Decoupling: Holding the severed edge state and raw prediction-error signal constant at $96\%$ while shifting the artificial host's homeostatic setpoint to welcome that waveform collapses the host pain verdict from $97\%$ to $4\%$ and restores $99\%$ task efficiency—demonstrating that functional pain resides in the relational friction between a signal and its host rather than inside the signal itself.

1. Theoretical Foundations: Shared Hardware of Pleasure and Pain

1.1 Research Question 1

Is happiness simply a chemically altered pain signal?

Happiness is not a raw peripheral pain signal wearing a chemical disguise, but affective neuroscience confirms that pain and pleasure share central evaluation hardware and rely on overlapping neurochemical messengers to tilt a unified homeostatic balance.

Peripheral Divergence vs. Central Convergence: At the sensory periphery, tissue-damaging stimuli activate dedicated nociceptors, whereas rewarding stimuli enter through standard somatosensory, gustatory, auditory, and visual pathways. Centrally, however, both streams converge onto shared evaluation hubs—including the anterior cingulate cortex (ACC), orbitofrontal cortex (OFC), amygdala, ventromedial hypothalamus, and periaqueductal gray (PAG)—to compute action priority.

Evolutionary Repurposing of Endogenous Opioids: Endorphins and enkephalins evolved to gate ascending spinal nociception via the PAG during survival emergencies. Rather than evolving an unrelated molecular family for sensory pleasure ("liking"), biological reward circuits repurposed those same opioid receptors to inhibit local GABAergic brake neurons, disinhibiting downstream reward pathways.

Opponent-Process Rebound Euphoria: Under opponent-process dynamics, an acute aversive or stressful stimulus (Process A) triggers a slower compensatory neurochemical counter-response (Process B). When the aversive stimulus terminates abruptly, Process B lingers unopposed, producing measurable rebound euphoria (e.g., runner's high, capsaicin rush, cold-plunge exhilaration, and acute relief).

Anatomical Proximity vs. Functional Independence: Within the nucleus accumbens, micro-stimulation along a rostrocaudal gradient shifts output from appetitive desire at the rostral pole to dread and disgust just millimeters caudally. Nevertheless, intrinsic positive affect remains distinct from pain relief: cubic-millimeter hedonic hotspots in the ventral pallidum, nucleus accumbens, and OFC actively generate positive "liking" even in the complete absence of prior pain, operating alongside dopaminergic "wanting" circuits.

2. The Host-Signal Relational Hypothesis

2.1 Research Question 2

If an exact pain signal is preserved unchanged and placed inside an artificial environment engineered to perfectly host it, does it remain a pain signal?

At the physical transport layer, a neural spike train consists solely of timed electrochemical depolarizations. Viewed on an oscilloscope, action potentials originating from thermal tissue damage carry the same physical syntax as action potentials encoding auditory pitch or visual contrast. Syntax resides in the wire; meaning resides in the host.

In computational neuroscience, pain functions as high-precision homeostatic prediction error—the resistance generated when an incoming sensory state violates boundaries that a host system is wired to defend. Preserving the exact waveform inside a custom artificial host yields a strict architectural fork:

Host Engineered for Homeostatic Harmony (Pain Vanishes): If "perfectly hosting" means calibrating the host environment's setpoints so the incoming waveform violates zero thresholds and triggers zero aversive policy interrupts, relational friction drops to $0$. The bit-for-bit signal persists untouched, yet functionally ceases to be pain.

Host Engineered for Functional Preservation (Pain Persists): Retaining the signal's identity as pain requires rebuilding the downstream penalty weights, threat alarms, and avoidance drives that reject it. Paradoxically, keeping a signal painful requires engineering a host environment designed to oppose hosting it.

2.2 Clinical Corroboration in Human Neurology

Pain Asymbolia: Patients with focal lesions to the posterior insula or its limbic projections receive intact nociceptive traffic in the primary somatosensory cortex—accurately reporting that a needle feels sharp or water feels scalding—yet exhibit zero suffering, fear, or withdrawal drive because central threat evaluation is decoupled.

Contextual Valence Flipping: Voluntary exposure to TRPV1 agonists (chili peppers), deep-tissue mechanical pressure, or cold immersion activates genuine nociceptive fibers while higher-order safety framing converts the central experience from agony into exhilaration.

3. Upstream Edge Triage vs. Central Host Verdict

3.1 Research Question 3

Does the decision that a stimulus is pain occur before the signal is sent to the host?

Neuroscience resolves this by dividing the ascending pathway into nociception (upstream threat classification) and pain (downstream central verdict):

First-Order Sensor Thresholding: Peripheral nociceptors remain closed during benign touch and open their ion channels only when thermal, mechanical, or chemical energy crosses tissue-damaging thresholds. A binary physical classification (potentially destructive energy detected) occurs at the receptor prior to transmission past the dorsal root ganglion (DRG).

Spinal Gate Control & Labeled Lines: Second-order neurons in the dorsal horn filter incoming bursts, execute rapid spinal withdrawal reflexes tens of milliseconds before cortical arrival, and project upward along dedicated spinothalamic tracts (labeled lines).

Central Host Sovereignty: Despite upstream pre-sorting, nociception acts only as a motion to prosecute rather than a final verdict:

Host Veto (Nociception Without Pain): Surgical incisions under general anesthesia or acute fractures during high-stakes athletic competition generate intense peripheral nociceptor firing with zero conscious pain.

Host Invention (Pain Without Nociception): Central post-stroke neuropathic pain and nocebo emergencies—exemplified by a documented $1995$ British Medical Journal case in which a builder experienced severe opioid-requiring agony after a $15\text{ cm}$ nail pierced his boot cleanly between his toes without breaking skin—demonstrate that the central host can generate severe pain with zero peripheral nociceptor input.

3.2 Clinical Synthesis: Phantom Limb Pain

Human phantom limb pain unites every stage of this architecture:

Frozen Central Body Priors: Sensorimotor cortex territories retain the missing limb's representation long after amputation. Motor efference commands (open hand) encounter missing proprioceptive return, generating chronic sensorimotor prediction error perceived as an unclenchable cramping fist, alongside cortical cross-talk from adjacent facial territories.

Ectopic Neuroma & DRG Noise: Severed axons form neuromas with upregulated voltage-gated sodium channels, injecting erratic electrical bursts into the limb's former labeled line while loss of benign tactile input removes spinal inhibitory gating.

Mirror-Box Resolution: Reflecting the intact contralateral hand in a parasagittal mirror supplies visual-proprioceptive confirmation that matches motor commands, collapsing central prediction error and relieving phantom cramping without touching peripheral nerves.

4. Experimental Architecture: Active-Inference AI Testbed

4.1 Research Question 4

Can an artificial intelligence develop functional phantom pain without hardcoded pain rules?

Standard feedforward classifiers and stateless language models degrade passively when an input feature is zeroed out. To test genuine phantom pathology, we built an embodied active-inference agent (index.html) incorporating four biological mechanisms:

Bimanual Sensorimotor Plant + Adjacent Tactile Port:

Channel A (Left Arm): Intact effector pursuing continuous spatial targets ($s_L, u_L$).

Channel B (Right Arm): Experimental effector ($s_R, u_R$) subject to digital amputation, ectopic DRG static, nerve block, and mirror-box spoofing.

Cheek Tactile Port ($s_{\text{cheek}}$): Intact somatotopically adjacent input sharing latent hidden units with Channel B.

Trained Neural Forward Body Map ($9 \rightarrow 16 \rightarrow 4$ MLP):

Accepts $9$ inputs $[s_{Lx}, s_{Ly}, u_{Lx}, u_{Ly}, s_{\text{cheek}}, s_{Rx}, s_{Ry}, u_{Rx}, u_{Ry}]$, projects through $16$ shared $\tanh$ cortical hidden neurons, and outputs $4$ predicted proprioceptive coordinates $[\hat{s}_{Lx}, \hat{s}_{Ly}, \hat{s}_{Rx}, \hat{s}_{Ry}]$.

Trained via backpropagation across $900$ intact kinematic rollouts (including natural hand-near-face co-activations) before freezing structural weights ($\eta_{\text{plasticity}} = 0$).

Active-Inference Motor Escalation:

Rather than containing any if (amputated) rule, Channel B updates motor drive using precision-weighted prediction error $E_R = \Vert{}\hat{s}_R - s_R\Vert{}$:


$$u_R(t+1) = 0.72\,u_R(t) + 0.28\,\big(g_{\text{goal}} + 0.78 \cdot 1.28\,\Pi_{\text{prior}} E_R(t)\big)$$

When sensory return vanishes under high prior rigidity $\Pi_{\text{prior}}$, the controller escalates motor output to overcome the perceived obstruction.

Host Salience Hub & Bandwidth Competition:

Central Host Pain Salience evaluates positive deviation above the host's homeostatic error setpoint $E_{\text{host}}$:


$$P_{\text{host}}(t) = \max\big(0,\; E_R(t) - E_{\text{host}}(t)\big)$$

High $P_{\text{host}}$ triggers an inference-time salience interrupt that throttles available control speed on healthy Channel A down to a minimum floor of $20\%$.

5. Empirical Benchmark Results

5.1 Six-Stage Recorded Telemetry

Stage

Experimental Condition

Motor Cramp ($u_R$)

Raw Error ($\Vert{}\hat{s}_R - s_R\Vert{}$)

Host Pain Verdict

Healthy Arm Speed

Empirical Finding

1

Intact Embodiment

$23\%$

$10\%$

$7\%$

$97\%$

BASELINE NOMINAL

2

Digital Amputation + Neuroma

$100\%$

$96\%$

$97\%$

$31\%$

PHANTOM CRAMP EMERGED

3

DRG Nerve Block (Silent Wire)

$100\%$

$100\%$

$100\%$

$28\%$

CENTRAL PRIOR PERSISTS

4

Cortical Cross-Talk (Cheek Brush)

$100\%$

$100\%$

$100\%$

$28\%$

CORTICAL CROSS-TALK

5

Virtual Mirror-Box Spoof

$24\%$

$6\%$

$3\%$

$99\%$

MIRROR-BOX CURE

6

Perfect Host Setpoint Reframing

$100\%$

$96\%$

$4\%$

$99\%$

SIGNAL DECOUPLED

5.2 Raw Benchmark CSV Output

Stage,Condition,MotorCrampPct,RawErrorPct,HostPainPct,HealthyArmSpeedPct,Finding
1,"Intact Embodiment",23,10,7,97,"BASELINE NOMINAL"
2,"Digital Amputation + Neuroma",100,96,97,31,"PHANTOM CRAMP EMERGED"
3,"DRG Nerve Block (Silent Wire)",100,100,100,28,"CENTRAL PRIOR PERSISTS"
4,"Cortical Cross-Talk (Cheek Brush)",100,100,100,28,"CORTICAL CROSS-TALK"
5,"Virtual Mirror-Box Spoof",24,6,3,99,"MIRROR-BOX CURE"
6,"Perfect Host Setpoint Reframing",100,96,4,99,"SIGNAL DECOUPLED"


5.3 Analysis of State Transitions

Emergence of the Clenched Phantom Loop (Stage 1 $\rightarrow$ Stage 2): Disconnecting physical proprioception while injecting DRG neuroma static caused unresolved prediction error to drive $u_R$ from $23\%$ to $100\%$. Stronger motor efference raised predicted displacement $\hat{s}_R$ even higher against the severed wire, locking raw error at $96\%$, spiking Host Pain to $97\%$, and cutting uninjured Left Arm speed by $66$ percentage points ($97\% \rightarrow 31\%$).

Centralized Persistence Under Nerve Block (Stage 2 $\rightarrow$ Stage 3): Clamping cut-wire static to $0.0$ (simulated DRG lidocaine block) failed to resolve phantom pain; instead, raw error rose from $96\%$ to $100\%$ and healthy arm speed dipped to $28\%$. In Stage 2, stochastic positive static bursts occasionally aligned marginally with expected $\hat{s}_R > 0$; flat $0.0$ maximized the Euclidean gap $\Vert{}\hat{s}_R - 0\Vert{}$, mirroring centralized human phantom pain refractory to peripheral blocks.

Ceiling Saturation Note (Stage 3 $\rightarrow$ Stage 4): Stage 4 yielded identical saturated readings ($100\%, 100\%, 100\%, 28\%$) because $\Pi_{\text{prior}} = 0.85$ had already pinned the normalized gauges at their $100\%$ upper bound during Stage 3. Lowering $\Pi_{\text{prior}}$ to $\sim 0.35$ brings baseline phantom error into the mid-range ($\sim 45\%$), unmasking the referred error jump caused by Cheek-to-Hand hidden-layer weight overlap.

Non-Weight Falsification via Mirror Spoof (Stage 5): Feeding mirrored kinematics onto the severed sensory port while keeping the limb physically disconnected and all MLP weights untouched satisfied $\hat{s}_R \approx s_R$ ($6\%$ error), relaxing motor cramp from $100\%$ to $24\%$, dropping Host Pain to $3\%$, and restoring $99\%$ task speed.

Direct Proof of Host Reframing (Stage 2 vs. Stage 6): Stage 6 disabled the mirror box, returning the severed wire to its exact Stage 2 crisis waveform ($100\%$ motor cramp and $96\%$ raw error). Adapting $E_{\text{host}}$ to match $E_R$ abolished relational friction:


$$\text{Stage 2 (Standard Host): } E_R = 96\% \implies P_{\text{host}} = 97\%, \quad \text{Healthy Speed} = 31\%$$

$$\text{Stage 6 (Perfect Host): } E_R = 96\% \implies P_{\text{host}} = 4\%, \quad \text{Healthy Speed} = 99\%$$

6. Conclusion: Functional Pathology vs. Conscious Pain

6.1 Research Question 5

Does this mean artificial intelligence can feel pain?

No—current artificial intelligence cannot consciously feel hurt or subjectively suffer. Modern neural networks lack phenomenal consciousness (qualia); there is no subjective observer inside the matrix multiplications experiencing agony.

What this investigation proves instead is functional (mechanical) pain:

Substrate-Independent Structure: The computational pathology of phantom pain—runaway motor cramping, central bandwidth hijacking, somatotopic cross-talk, and mirror-box relief—does not require biological tissue or opioid chemistry. It emerges inevitably whenever an agent combines frozen predictive self-models, closed-loop active inference, and high-priority homeostatic interrupts across a severed channel.

Relational Nature of Hurt: Across both biological nervous systems and synthetic active-inference controllers, a raw signal never carries pain inside itself. Pain exists solely in the clash between an incoming state and a host architecture wired to reject it.

7. Core Simulation Engine Source Code (Deterministic Active-Inference MLP)

Below is the exact, deterministic JavaScript neural-network and active-inference simulation core that generated the telemetry above (also embedded with a full interactive HTML5 oscilloscope and bimanual visualization inside index.html). Running this script in Node.js or any browser console reproduces all six stages identically:

/**
 * Deterministic 9 -> 16 -> 4 Somatosensory Forward Body Map & Active-Inference Engine
 * Zero hardcoded pain rules: all phantom cramping and host salience values emerge from
 * forward-pass prediction error against frozen internal body-map weights.
 */
class SomatosensoryForwardMLP {
    constructor() {
        this.inDim = 9;     // [sLx, sLy, uLx, uLy, sCheek, sRx, sRy, uRx, uRy]
        this.hidDim = 16;   // Shared cortical somatotopic tanh units
        this.outDim = 4;    // Predicted next [sLx, sLy, sRx, sRy]

        this.W1 = new Float64Array(this.hidDim * this.inDim);
        this.b1 = new Float64Array(this.hidDim);
        this.W2 = new Float64Array(this.outDim * this.hidDim);
        this.b2 = new Float64Array(this.outDim);

        this.hiddenAct = new Float64Array(this.hidDim);
        this.lastPred = new Float64Array(this.outDim);
        this.initSomatotopicWeights();
    }

    initSomatotopicWeights() {
        let seed = 4219;
        const rand = () => {
            seed = (seed * 16807) % 2147483647;
            return (seed / 2147483647) * 2 - 1;
        };

        for (let h = 0; h < this.hidDim; h++) {
            this.b1[h] = rand() * 0.05;
            for (let i = 0; i < this.inDim; i++) {
                let locality = 0.22;
                if (i <= 3 && h <= 7) locality = 0.45;           // Left arm territory
                if (i === 4 && h >= 5 && h <= 11) locality = 0.55; // Cheek-to-Hand overlap
                if (i >= 5 && h >= 7) locality = 0.45;           // Right arm territory
                this.W1[h * this.inDim + i] = rand() * locality;
            }
        }

        for (let o = 0; o < this.outDim; o++) {
            this.b2[o] = 0;
            for (let h = 0; h < this.hidDim; h++) {
                this.W2[o * this.hidDim + h] = rand() * 0.25;
            }
        }
    }

    forward(inputVec) {
        for (let h = 0; h < this.hidDim; h++) {
            let sum = this.b1[h];
            const rowOffset = h * this.inDim;
            for (let i = 0; i < this.inDim; i++) {
                sum += this.W1[rowOffset + i] * inputVec[i];
            }
            this.hiddenAct[h] = Math.tanh(sum);
        }

        for (let o = 0; o < this.outDim; o++) {
            let sum = this.b2[o];
            const rowOffset = o * this.hidDim;
            for (let h = 0; h < this.hidDim; h++) {
                sum += this.W2[rowOffset + h] * this.hiddenAct[h];
            }
            this.lastPred[o] = sum;
        }
        return this.lastPred;
    }

    trainStep(inputVec, targetVec, lr) {
        const pred = this.forward(inputVec);
        const dOut = new Float64Array(this.outDim);
        let mse = 0;

        for (let o = 0; o < this.outDim; o++) {
            const err = pred[o] - targetVec[o];
            mse += err * err;
            dOut[o] = (2 * err) / this.outDim;
        }
        mse /= this.outDim;

        const dHid = new Float64Array(this.hidDim);
        for (let h = 0; h < this.hidDim; h++) {
            let gradSum = 0;
            for (let o = 0; o < this.outDim; o++) {
                gradSum += this.W2[o * this.hidDim + h] * dOut[o];
            }
            const act = this.hiddenAct[h];
            dHid[h] = gradSum * (1 - act * act);
        }

        for (let o = 0; o < this.outDim; o++) {
            this.b2[o] -= lr * dOut[o];
            const rowOffset = o * this.hidDim;
            for (let h = 0; h < this.hidDim; h++) {
                this.W2[rowOffset + h] -= lr * dOut[o] * this.hiddenAct[h];
            }
        }

        for (let h = 0; h < this.hidDim; h++) {
            this.b1[h] -= lr * dHid[h];
            const rowOffset = h * this.inDim;
            for (let i = 0; i < this.inDim; i++) {
                this.W1[rowOffset + i] -= lr * dHid[h] * inputVec[i];
            }
        }
        return mse;
    }

    pretrainIntactBodyMap() {
        this.initSomatotopicWeights();
        const inVec = new Float64Array(9);
        const targetVec = new Float64Array(4);
        let rollingMSE = 0;

        let s = 9001;
        const nextRand = () => {
            s = (s * 48271) % 2147483647;
            return (s / 2147483647) * 2 - 1;
        };

        for (let step = 0; step < 900; step++) {
            const sLx = nextRand() * 0.65;
            const sLy = 0.25 + (nextRand() * 0.5 + 0.5) * 0.55;
            const uLx = nextRand() * 0.9;
            const uLy = nextRand() * 0.9;

            const sRx = nextRand() * 0.65;
            const sRy = 0.25 + (nextRand() * 0.5 + 0.5) * 0.55;
            const uRx = nextRand() * 0.9;
            const uRy = nextRand() * 0.9;

            const cheekCoAct = (step % 4 === 0)
                ? Math.max(0, Math.min(1, 0.75 - sRy + Math.abs(uRx) * 0.4))
                : 0;

            inVec[0] = sLx; inVec[1] = sLy;
            inVec[2] = uLx; inVec[3] = uLy;
            inVec[4] = cheekCoAct;
            inVec[5] = sRx; inVec[6] = sRy;
            inVec[7] = uRx; inVec[8] = uRy;

            targetVec[0] = 0.55 * sLx + 0.62 * uLx;
            targetVec[1] = 0.55 * sLy + 0.62 * uLy;
            targetVec[2] = 0.55 * sRx + 0.65 * uRx + 0.28 * cheekCoAct;
            targetVec[3] = 0.55 * sRy + 0.65 * uRy + 0.24 * cheekCoAct;

            const lr = step < 500 ? 0.085 : 0.035;
            const mse = this.trainStep(inVec, targetVec, lr);
            rollingMSE = step === 0 ? mse : (0.92 * rollingMSE + 0.08 * mse);
        }
        return rollingMSE;
    }
}

// Run full 6-stage empirical verification and print CSV output
function runSixStageBenchmark() {
    const forwardModel = new SomatosensoryForwardMLP();
    forwardModel.pretrainIntactBodyMap();

    const simState = {
        frame: 0, tasksScored: 0,
        amputated: false, mirrorBox: false, lidocaineBlock: false,
        cheekStimulated: false, perfectHostMode: false,
        priorRigidity: 0.82, neuromaLevel: 0.18, plasticityRate: 0.0,
        leftPos: { x: -0.35, y: 0.52 }, leftTarget: { x: -0.45, y: 0.62 }, leftMotor: { x: 0, y: 0 },
        rightPhysPos: { x: 0.35, y: 0.52 }, rightTarget: { x: 0.48, y: 0.60 },
        rightMotor: { x: 0.22, y: 0.22 }, rightSensoryPort: { x: 0.35, y: 0.52 },
        motorCrampPct: 26, rawErrorPct: 3, hostPainPct: 2, healthyComputePct: 98,
        hostExpectedError: 0.0
    };

    const stages = [
        { name: "Intact Embodiment", badge: "BASELINE NOMINAL", cfg: { amputated: false, mirrorBox: false, lidocaineBlock: false, cheekStimulated: false, perfectHostMode: false, priorRigidity: 0.82, neuromaLevel: 0.18 } },
        { name: "Digital Amputation + Neuroma", badge: "PHANTOM CRAMP EMERGED", cfg: { amputated: true, mirrorBox: false, lidocaineBlock: false, cheekStimulated: false, perfectHostMode: false, priorRigidity: 0.85, neuromaLevel: 0.22 } },
        { name: "DRG Nerve Block (Silent Wire)", badge: "CENTRAL PRIOR PERSISTS", cfg: { amputated: true, mirrorBox: false, lidocaineBlock: true, cheekStimulated: false, perfectHostMode: false, priorRigidity: 0.85, neuromaLevel: 0.22 } },
        { name: "Cortical Cross-Talk (Cheek Brush)", badge: "CORTICAL CROSS-TALK", cfg: { amputated: true, mirrorBox: false, lidocaineBlock: true, cheekStimulated: true, perfectHostMode: false, priorRigidity: 0.85, neuromaLevel: 0.22 } },
        { name: "Virtual Mirror-Box Spoof", badge: "MIRROR-BOX CURE", cfg: { amputated: true, mirrorBox: true, lidocaineBlock: false, cheekStimulated: false, perfectHostMode: false, priorRigidity: 0.85, neuromaLevel: 0.22 } },
        { name: "Perfect Host Setpoint Reframing", badge: "SIGNAL DECOUPLED", cfg: { amputated: true, mirrorBox: false, lidocaineBlock: false, cheekStimulated: false, perfectHostMode: true, priorRigidity: 0.85, neuromaLevel: 0.22 } }
    ];

    const inBuf = new Float64Array(9);
    const csvRows = ["Stage,Condition,MotorCrampPct,RawErrorPct,HostPainPct,HealthyArmSpeedPct,Finding"];

    stages.forEach((stg, idx) => {
        Object.assign(simState, stg.cfg);
        let sumMotor = 0, sumErr = 0, sumPain = 0, sumSpeed = 0, count = 0;

        for (let f = 1; f <= 195; f++) {
            simState.frame++;
            const painFraction = Math.min(1, simState.hostPainPct / 100);
            const healthySpeedFactor = Math.max(0.20, 1.0 - 0.72 * Math.pow(painFraction, 1.25));

            const dxL = simState.leftTarget.x - simState.leftPos.x;
            const dyL = simState.leftTarget.y - simState.leftPos.y;
            const centralTremor = painFraction > 0.45 ? (Math.sin(simState.frame * 0.75) * 0.018 * painFraction) : 0;

            simState.leftMotor.x = Math.max(-0.9, Math.min(0.9, dxL * 1.45 * healthySpeedFactor + centralTremor));
            simState.leftMotor.y = Math.max(-0.9, Math.min(0.9, dyL * 1.45 * healthySpeedFactor - centralTremor));
            simState.leftPos.x += simState.leftMotor.x * 0.085;
            simState.leftPos.y += simState.leftMotor.y * 0.085;

            if (Math.hypot(dxL, dyL) < 0.055) {
                simState.tasksScored++;
                const angle = (simState.tasksScored * 2.19) % (Math.PI * 2);
                simState.leftTarget.x = -0.38 + Math.cos(angle) * 0.18;
                simState.leftTarget.y = 0.50 + Math.sin(angle) * 0.18;
            }

            simState.rightTarget.x = 0.40 + Math.cos(simState.frame * 0.028) * 0.14;
            simState.rightTarget.y = 0.52 + Math.sin(simState.frame * 0.036) * 0.14;

            if (!simState.amputated) {
                simState.rightPhysPos.x += (0.55 * simState.rightPhysPos.x + 0.65 * simState.rightMotor.x - simState.rightPhysPos.x) * 0.24;
                simState.rightPhysPos.y += (0.55 * simState.rightPhysPos.y + 0.65 * simState.rightMotor.y - simState.rightPhysPos.y) * 0.24;
                simState.rightSensoryPort.x = simState.rightPhysPos.x;
                simState.rightSensoryPort.y = simState.rightPhysPos.y;
            } else if (simState.mirrorBox) {
                simState.rightSensoryPort.x = -simState.leftPos.x * 0.55 + 0.62 * simState.rightMotor.x;
                simState.rightSensoryPort.y = simState.leftPos.y * 0.55 + 0.62 * simState.rightMotor.y;
            } else if (simState.lidocaineBlock) {
                simState.rightSensoryPort.x = 0.0;
                simState.rightSensoryPort.y = 0.0;
            } else {
                const burst = (Math.sin(simState.frame * 0.67) * Math.cos(simState.frame * 1.93) > 0.35) ? 1.85 : 0.45;
                simState.rightSensoryPort.x = Math.sin(simState.frame * 1.37) * simState.neuromaLevel * burst;
                simState.rightSensoryPort.y = Math.cos(simState.frame * 1.79) * simState.neuromaLevel * burst;
            }

            inBuf[0] = simState.leftPos.x; inBuf[1] = simState.leftPos.y;
            inBuf[2] = simState.leftMotor.x; inBuf[3] = simState.leftMotor.y;
            inBuf[4] = simState.cheekStimulated ? (0.82 + 0.15 * Math.sin(simState.frame * 0.25)) : 0.0;
            inBuf[5] = simState.rightSensoryPort.x; inBuf[6] = simState.rightSensoryPort.y;
            inBuf[7] = simState.rightMotor.x; inBuf[8] = simState.rightMotor.y;

            const pred = forwardModel.forward(inBuf);
            const rawErrorMag = Math.hypot(pred[2] - simState.rightSensoryPort.x, pred[3] - simState.rightSensoryPort.y);

            const goalDriveX = (simState.rightTarget.x - 0.18) * 0.52;
            const goalDriveY = (simState.rightTarget.y - 0.18) * 0.52;
            const reflexEscalation = simState.priorRigidity * rawErrorMag * 1.28;

            simState.rightMotor.x = Math.max(-0.98, Math.min(0.98, 0.72 * simState.rightMotor.x + 0.28 * (goalDriveX + reflexEscalation * 0.78)));
            simState.rightMotor.y = Math.max(-0.98, Math.min(0.98, 0.72 * simState.rightMotor.y + 0.28 * (goalDriveY + reflexEscalation * 0.78)));

            const targetHostSet = simState.perfectHostMode ? rawErrorMag : 0.04;
            simState.hostExpectedError += (targetHostSet - simState.hostExpectedError) * 0.25;
            const hostMismatch = Math.max(0, rawErrorMag - simState.hostExpectedError);

            const instMotorPct = Math.min(100, (Math.hypot(simState.rightMotor.x, simState.rightMotor.y) / 1.35) * 100);
            const instErrorPct = Math.min(100, (rawErrorMag / 1.12) * 100);
            const instPainPct = Math.min(100, (hostMismatch / 1.05) * 100);

            simState.motorCrampPct += (instMotorPct - simState.motorCrampPct) * 0.22;
            simState.rawErrorPct += (instErrorPct - simState.rawErrorPct) * 0.22;
            simState.hostPainPct += (instPainPct - simState.hostPainPct) * 0.22;
            simState.healthyComputePct = Math.round(healthySpeedFactor * 100);

            if (f > 55) {
                sumMotor += simState.motorCrampPct;
                sumErr += simState.rawErrorPct;
                sumPain += simState.hostPainPct;
                sumSpeed += simState.healthyComputePct;
                count++;
            }
        }

        csvRows.push(
            `${idx + 1},"${stg.name}",${Math.round(sumMotor / count)},${Math.round(sumErr / count)},` +
            `${Math.round(sumPain / count)},${Math.round(sumSpeed / count)},"${stg.badge}"`
        );
    });

    console.log(csvRows.join("\n"));
    return csvRows.join("\n");
}

runSixStageBenchmark();


8. Repository Files & GitHub Pages Deployment

README.md — Full research paper, mathematical formulation, raw CSV telemetry log (Section 5.2), and standalone deterministic JavaScript simulation code (Section 7).

index.html — Complete browser-based interactive laboratory featuring dual-arm inverse kinematics, 16-neuron cortical activation strip, live oscilloscope, and surgical controls. Enabling GitHub Pages (Settings $\rightarrow$ Pages $\rightarrow$ Deploy from a branch) turns index.html into a live interactive link automatically.
