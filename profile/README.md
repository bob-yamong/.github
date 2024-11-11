# BoB 13th Project - Team Yamong_1337

Development of an eBPF-based container runtime solution

## Project Structure
![eBPF Flow](/../../../../bob-yamong/drawio/blob/main/img/yamong/yamong.png)
![Data Flow](/../../../../bob-yamong/drawio/blob/main/img/yamong/yamong-v2.png)

## WBS

```mermaid
gantt
    title WBS
    dateFormat YYYY-MM-DD
    todayMarker off

    section Initiation
    Planning         :2024-09-02, 5d
    Kick-off         :2024-09-02, 5d

    section Research
    Kernel Study        :2024-09-02, 10d
    eBPF Study          :2024-09-02, 10d
    Prior Research Survey :2024-09-07, 5d

    section Development
    Analysis of Kernel API     :2024-09-07, 10d
    Analysis of lsm hooks      :2024-09-07, 10d
    Kernel Space Program       :2024-09-17, 14d
    User Spcae Program         :2024-09-30, 14d
    Policy YAML parser         :2024-09-30, 14d
    eBPF Security Engine MVP   :2024-10-11, 8d
    1st Interim Presentation       :2024-10-11, 8d
    Policy Page Dev :2024-10-19, 5d
    Container Moinotring Page Dev :2024-10-24, 5d
    BE Dev           :2024-10-29, 18d 
    Security Enhance :2024-10-29, 18d
    2nd Interim Presentation       :2024-11-09, 7d
    Event Log Dev    :2024-11-16, 14d
    Solution Enhance :2024-11-16, 28d

    section Verification
    Testing          :2024-12-07, 14d
    Verification     :2024-12-07, 14d
    Report Writing   :2024-12-07, 14d

    section Wrap-up
    Final Presentation    :2024-12-21, 1d
```


## Contributor
* PM: Changhyun Lee ([eeche](https://github.com/eeche))
* Yejune Ko ([koyejune0302](https://github.com/KoYejune0302))
* HyeonSeok Kim ([persona-twotwo](https://github.com/persona-twotwo))
* Mingyu Jeong ([tomorrow9913](https://github.com/tomorrow9913))
* SungHyun Jeon ([nukunga](https://github.com/nukunga))
* Harksu Lim ([harksu](https://github.com/harksu))
